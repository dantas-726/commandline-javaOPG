# commandline-in-Java

**Command line to download a game on steam made by me (in development)**

>**This code is based on the size of your monitor

>**My Monitor:** 
- AOC 144hz
   - Resolution: 1920x1080
     - 24 inch



```
import java.awt.AWTException;
import java.awt.Robot;
import java.awt.event.KeyEvent;
public class exemplo {

	public static void main(String[] args) throws AWTException 
	{ 
		Robot robo = new Robot();
		
		robo.delay(500);
		
		robo.mouseMove(560,1064);
		
		robo.mousePress(KeyEvent.BUTTON1_DOWN_MASK);
		robo.mouseRelease(KeyEvent.BUTTON1_DOWN_MASK);
		
		robo.delay(1000);
		
		robo.mouseMove(117, 180);
		
		robo.delay(1000);
		
		robo.mousePress(KeyEvent.BUTTON1_DOWN_MASK);
		robo.mouseRelease(KeyEvent.BUTTON1_DOWN_MASK);
		
		robo.delay(1500);
		
		
		robo.keyPress(KeyEvent.VK_R);
		robo.keyRelease(KeyEvent.VK_R);
		
		robo.delay(1);
		
		robo.keyPress(KeyEvent.VK_A);
		robo.keyRelease(KeyEvent.VK_A);
		
		robo.delay(1);
		
		robo.keyPress(KeyEvent.VK_F);
		robo.keyRelease(KeyEvent.VK_F);
		
		robo.delay(1);
		
		robo.keyPress(KeyEvent.VK_T);
		robo.keyRelease(KeyEvent.VK_T);
		
		
		robo.mouseMove(60, 271);
		
		robo.mousePress(KeyEvent.BUTTON1_DOWN_MASK);
		robo.mouseRelease(KeyEvent.BUTTON1_DOWN_MASK);
		
		robo.delay(1000);
		
		
		robo.mouseMove(400, 441);
		
		robo.mousePress(KeyEvent.BUTTON1_DOWN_MASK);
		robo.mouseRelease(KeyEvent.BUTTON1_DOWN_MASK);
		
		robo.delay(1000);
		
		robo.keyPress(KeyEvent.VK_ENTER);
		robo.keyRelease(KeyEvent.VK_ENTER);
		
		robo.delay(5000);
		
		robo.mouseMove(1144, 692);
		
		robo.mousePress(KeyEvent.BUTTON1_DOWN_MASK);
		robo.mouseRelease(KeyEvent.BUTTON1_DOWN_MASK);
		
		robo.delay(500);
		
		robo.mouseMove(140, 269);
		
		robo.mousePress(KeyEvent.BUTTON1_DOWN_MASK);
		robo.mouseRelease(KeyEvent.BUTTON1_DOWN_MASK);
		
		robo.delay(500);
		
		robo.keyPress(KeyEvent.VK_DELETE);
		

		
	

	}

}
```
