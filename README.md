# java
java课程上机代码
import java.io.File;


public class MyFirstProgram
{   public static void main( String[] args)
   {       System.out.println("学号姓名调试的的第一个应用程序");
   File file=new File("E:\\上机1\\18软工x班xx号xxx上机报告1.doc");
   if(file.exists())
   {
   file.renameTo(new File("E:\\上机1\\18软工6班39号严子浩上机报告1.doc"));
   }
   } 
}
