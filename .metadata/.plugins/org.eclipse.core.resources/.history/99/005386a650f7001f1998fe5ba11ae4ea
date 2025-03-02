package hooks;

import java.io.IOException;

import org.junit.After;

import demoblaze.utils.Base;
import io.cucumber.java.Before;

public class Hooks extends Base{
	Base base = new Base();
	 @Before
	    public void setup() throws IOException {
	        
			base.configBeforeMethod();
	         Base.prop("url"); 
	    }

	    @After
	    public void teardown() {
	    	base.configAfterMethod();
	    }
}
