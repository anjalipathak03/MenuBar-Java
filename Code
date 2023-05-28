import java.awt.*;
public class MyMenu
{
  public static void main(String arg[])
{ 
Frame fr = new Frame();
MenuBar mb = new MenuBar();
Menu file = new  Menu("FILE");
MenuItem new1= new MenuItem("New");
MenuItem open= new MenuItem("Open");
MenuItem save= new MenuItem("Save");

file.add(new1);
file.add(open);
file.add(save);

mb.add(file);

Menu edit = new Menu("EDIT");
MenuItem cut = new MenuItem("Cut");
MenuItem copy = new MenuItem("Copy");
MenuItem paste = new MenuItem("Paste");
edit.add(cut);
edit.add(copy);
edit.add(paste);

mb.add(edit);
fr.setMenuBar(mb);
fr.setVisible(true);
fr.setSize(500,500);
}
}
