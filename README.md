# ZohoAutomation

package com.zoho;




import login.LoginZoho;

public class ZohoPresentation {
	
	public static void main(String[] args) {
		
		
		LoginZoho loginZoho = new LoginZoho();
		loginZoho.setAuthentication("db4ee6c4eb99a25da606fdbec25497658016fe29448c2798b53e0ea9e85e671d64ae5b78db47101daa9f43be2ecc2f45f1e0d539a3c2ee40bb24f28ddf2cfb53", "ba0a57f41a7d77b1394adb7fa421eb54bcd84ad5b10a40adb20b671136503033de4375ec706b85b9746b241e6eb8f3ece75383950c42d70bd563138a7b0b787d", "C:\\Users\\user\\eclipse-workspace\\ZohoTest\\Driver\\chromedriver.exe");
		
	}

}
