package practical;

import org.openqa.selenium.By;
import org.openqa.selenium.Keys;
import org.openqa.selenium.WebElement;
import org.openqa.selenium.chrome.ChromeDriver;
import org.openqa.selenium.support.ui.Select;

public class fornof {
	
	ChromeDriver driver;
	void launch() {
	 driver=new ChromeDriver();
	 driver.manage().window().maximize();
	 driver.get("https://demoqa.com/automation-practice-form");
}
	void form() {
		
	driver.findElement(By.id("firstName")).sendKeys("ajay");
    driver.findElement(By.id("lastName")).sendKeys("gonate");
    driver.findElement(By.id("userEmail")).sendKeys("ajay@2003");
    
    driver.findElement(By.xpath("//*[@id=\"genterWrapper\"]/div[2]/div[1]/label")).click();
    
    driver.findElement(By.id("userNumber")).sendKeys("9876543210");

    
    driver.findElement(By.id("dateOfBirthInput")).sendKeys(Keys.CONTROL + "a");
	driver.findElement(By.id("dateOfBirthInput")).sendKeys("1 aug 2000");
	driver.findElement(By.id("dateOfBirthInput")).sendKeys(Keys.ENTER);
    
    WebElement subjects = driver.findElement(By.id("subjectsInput"));
    subjects.sendKeys("Maths");
    subjects.sendKeys(Keys.ENTER);

    driver.findElement(By.xpath("//*[@id=\"hobbiesWrapper\"]/div[2]/div[1]/label")).click();
    
    WebElement upload = driver.findElement(By.id("uploadPicture"));
    upload.sendKeys("C:\\Users\\ajay gonate\\OneDrive\\Desktop\\practise");


    driver.findElement(By.id("currentAddress")).sendKeys("kothrud ,pune");
    
    driver.findElement(By.xpath("//*[@id=\"state\"]/div/div[1]/div[1]"));

    driver.findElement(By.id("submit")).click();
    

    
    


}

public static void main(String[] args) {
	fornof o=new fornof();
	o.launch();
	o.form();
}
}




