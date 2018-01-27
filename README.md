# redventuresassignment

RV Automation Assignment Leah Mooney

Instructions

The test scripts should be written in Java Eclipse Oxygen
Add a jar for the Selenium standalone server
>Build Path Configure 
>Build Path 
>Java Build Path 
>Click the 'Libraries' tab on the top 
>Add External JARs
Right click the project
>Run As Java Application 
FireFox Browser should load the Frontier website

Background/Approach 
Over the past couple months I have become familiar with manual testing on video gateway devices; primarily running manual test scripts, entering product defects, familiarization with software development life cycle, agile/devops concepts, and test applications such as JIRA and ALM. As a result of an informal training program with Infosys/Comcast teams, I have decided to more formally pursue job opportunities in software test. During this time my exposure to automation testing, tooling and programming languages has been limited.

Because this was my first time working with automation testing and writing test scripts, I've conducted a fair amount of research/self-study to get more comfortable with various processes. I used Java Eclipse Oxygen to write the test scripts and added the Selenium standalone server to run the tests. I used xpath to find exact locations on the website to then plug back in the test scripts.

Even though I don't have a lot of experience with automation testing, I very much enjoyed working on this project and am eager to keep learning. Thank you for taking the time to review my assignment.

Bonus

For different browsers: 
Chrome will use ChromeDriver 
Safari will use SafariDriver 
Internet Explorer will use InternetExplorerDriver

Actual Errors 
The only thing I found interesting was when letters were entered instead of numbers for the zip code, the user will not be given a message to enter a valid zip code. When the user leaves the box blank, a message does appear, "Address is required." When actual numbers are entered, the page redirects the user to the next page successfully.



package automationtesting;

public class FrontierTesting {
    
      import org.openqa.selenium.By;
      import org.openqa.selenium.WebDriver;
      import org.openqa.selenium.firefox.FirefoxDriver;

public void CheckImage() throws Exception {

      //
      WebDriver driver=new FirefoxDriver();
      
      driver.get("https://internet.frontier.com/");
      
      driver.manage().window().maximize().
      
      WebElement ImageFile = driver.findElement(By.xpath(//*[@id="js-track-logo"]));
      
      WebElement ImageFile = driver.findElement(By.xpath(/html/body/main/div/section));
      
      WebElement ImageFile = driver.findElement(By.xpath(/html/body/main/section[1]/div[2]/div[1]/div/div));
      
      WebElement ImageFile = driver.findElement(By.xpath(/html/body/main/section[1]/div[2]/div[2]/div/div));
      
      WebElement ImageFile = driver.findElement(By.xpath(/html/body/main/section[1]/div[2]/div[3]/div/div));
      
      WebElement ImageFile = driver.findElement(By.xpath(/html/body/main/section[1]/div[2]/div[4]/div/div));
      
      WebElement ImageFile = driver.findElement(By.xpath(/html/body/main/section[2]));
      
      WebElement ImageFile = driver.findElement(By.xpath(/html/body/main/div/section[3]));
      
}
      
public static void main(String[] args) {
      
              \(?\d{3}\)?[-.\s]?\d{3}[-.\s]?\{4}
              
              $\.?d{2}
              
              driver.findElement(By.xpath(//*[@id="countdown"]));
              
}
      
public static void main(String[] args) {
      
      driver.findElement(By.xpath(//*@id="zip"))
      
              driver.findElement(By.xpath(/html/body/main/section[2]/div/div/div/div/div/form/p));
              
              driver.findElement(By.xpath(///*@id="zip")).sendKeys(abcde);
              
              driver.findElement(By.xpath(/html/body/main/div[1]/section/div/div/div/div[2]/div/h3)).sendKeys(18902);
              
}

public static void main(String[] args) {

      driver.findElement(By.xpath("//*[@id="js-track-nav-shop-online"]")).click();
      
      driver.findElement(By.xpath("//*[@id="js-track-form-check-availability"]")).click();
      
      driver.findElement(By.xpath("//*[@id="js-track-home-hero"]")).click();
      
      driver.findElement(By.xpath("//*[@id="js-track-home-shop-plans"]")).click();
      
      driver.findElement(By.xpath("//*[@id="js-track-home-shop-internet"]")).click();
      
      driver.findElement(By.xpath("//*[@id="js-track-home-shop-tv"]")).click();
      
      driver.findElement(By.xpath("//*[id"js-track-home-shop-plans"]")).click();
      
      driver.findElement(By.xpath("//*[id"js-track-home-shop-bundles"]")).click();
      
}
      
public static void main(String[] args) {

    SpellChecker checker = new SpellChecker();
    
}

public static void Hover(WebDriver driver, WebElement element) {
      Actions action = new Actions(driver);
      action.moveToElement(element).perform();
      
}

public static void HoverAndClick(WebDriver driver, WebElement elementToHover, WebElement elementToClick) {
      Actions action = new Actions(driver);
      action.moveToElement(element).perform();
      
}
      
public static void main(String[] args) {
      assertTrue(driver.findElement(By.id(https://internet.frontier.com/).getAttribute("class").contains("active"));
      
      WebElement click = driver.findElement(By.xpath("//*[@id="js-track-nav-shop-online"]"));click.click();
      
      WebElement click = driver.findElement(By.xpath("//*[@id="js-track-form-check-availability"]"));click.click();
      
      WebElement click = driver.findElement(By.xpath("//*[@id="js-track-home-hero"]"));click.click();
      
      WebElement click = driver.findElement(By.xpath("//*[@id="js-track-home-shop-plans"]"));click.click();
      
      WebElement click = driver.findElement(By.xpath("//*[@id="js-track-home-shop-internet"]"));click.click();
      
      WebElement click = driver.findElement(By.xpath("//*[@id="js-track-home-shop-tv"]"));click.click();
     
      WebElement click = driver.findElement(By.xpath("//*[@id="js-track-home-shop-plans"]"));click.click();
      
}

}