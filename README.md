import java.awt.Robot;
import java.awt.event.InputEvent;
 
 
public class mouse{
 
 public static void main(String[] args) throws Exception {
 
            Robot robot = new Robot();
            
 
            // SET THE MOUSE X Y POSITION
            while(true){
            robot.mouseMove(600, 350);   
            robot.mousePress(InputEvent.BUTTON3_MASK);
            robot.mouseRelease(InputEvent.BUTTON3_MASK);
            Thread.sleep(5000);
            robot.mouseMove(650, 300);
            Thread.sleep(5000);
            robot.mouseMove(400, 550);
            robot.mousePress(InputEvent.BUTTON1_MASK);
            robot.mouseRelease(InputEvent.BUTTON1_MASK);
            Thread.sleep(5000);
            robot.mouseMove(550, 300);
            Thread.sleep(5000);
            robot.mouseMove(400, 550);
            Thread.sleep(5000);
            robot.mouseMove(550, 300);
            
            }
 
 }
