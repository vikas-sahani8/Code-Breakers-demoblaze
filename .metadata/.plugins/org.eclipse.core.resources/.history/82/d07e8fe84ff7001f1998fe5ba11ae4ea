package runners;

import org.junit.runner.RunWith;
import io.cucumber.junit.Cucumber;
import io.cucumber.junit.CucumberOptions;

@RunWith(Cucumber.class)
@CucumberOptions(
    features = "src/test/resources/features", 
    glue = {"stepDefinition", "Hooks"},  
    monochrome = true,  
    plugin = { 
        "pretty", 
        "html:target/HtmlReports.html", 
        "json:target/cucumber.json",
        "junit:target/cucumber.xml"
    }
)
public class MyTestRunner {
	
}
