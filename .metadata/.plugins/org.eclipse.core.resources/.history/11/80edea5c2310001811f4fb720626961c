package com.KeximBank.master;

import org.openqa.selenium.WebElement;
import org.openqa.selenium.support.FindBy;

public class KeximBankHP {
	//Element properties
	//UserName element
	@FindBy (id = "txtuId") 
	WebElement userName;
	
	//Enter password
	@FindBy (id = "txtPword") 
	WebElement pwd;
	
	//Enter password
	@FindBy (id = "login") 
	WebElement login;
	
	//Login with valid user
	public void login(String username, String password){
		userName.sendKeys(username);
		pwd.sendKeys(password);
		login.click();
	}
}
