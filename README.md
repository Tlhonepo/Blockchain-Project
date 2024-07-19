# Blockchain-Project
This app leverages blockchain technology to create a secure and decentralized platform for healthcare data exchange, ensuring data privacy, interoperability, and efficient handling of medical information.
NOTE: 
Below is the youtube link to the Unlisted Video describing the project

YOUTUBE LINK[COPY AND OPEN LINK IN WEBBROWSER]: https://youtu.be/diy1Q4Pnikc

APPS THAT MUST BE DOWNLOADED IN ORDER FOR THE PROJECT TO COMPILE AND RUN SUCCESSFULLY

1.) XAMPP CONTROL PANEL

   DOWNLOAD LINK => Direct Download Link: https://www.apachefriends.org/
   ALTERNATE => Google Drive Link: https://drive.google.com/file/d/1DTrNbmV6mEE26aiLos4yZKn4IN39FUJ9/view?usp=sharing
   
2.) MYSQL Connector => Direct Download Link: https://dev.mysql.com/downloads/file/?id=527658
	               Select No thanks, just start my download.

	Since the jar file for the mysql connector is in the dist file => Take the file path of where the jar would be 
						Right Click on the project in eclipse=>=>Build Path=>Configure build path=>Libraries=>Click on Classpath->Add Jar =>Pick the MiniProject folder=>dist file=>Finaly select that mysql jar file
   
 3) Same Analogy to the blockchain jar file in the dist file
		Java (JVM) Argument:--module-path "C:\javafx-sdk-21.0.2\lib" --add-modules javafx.base,javafx.controls,javafx.fxml,javafx.graphics,javafx.media
   
   
   After Installation of XAMPP, click Start Apache and click Start mySQL, from there click "admin" on the row with mySQL Start button.
   
   Create database called: mydatabase
   Followed by 4 tables namely: [Ensure that the names of the columns a written exactly the same as the ones below]

    A.    blockchain => 1 column
		Called	 Transcations	->of Type Text
	
	B.    authorized_doctors => 4 columns
	Called:      Username -> of type Text
				 EmailAddress -> of type Text
				 Qualification -> of type Text
				 Description -> of type Text
				 Address -> of type Text
	
	
	C.    regboard => 3 columns
	Called:      Username -> of type Text
				Password -> if type Text
				Email -> of type Text
	
	D.    board => 14 column
	Called:		ID -> of type Text
				Patient Name -> of type Text
				Gender -> of type Text
				Age -> of type int => length 2 
				Diagnosis -> of type Text
				Treatment -> -> of type Text
				Phone Number -> of type int =>lenth 10 
				Height -> of type varchar = length 10
				Weight -> of type varchar = length 10
				Blood Type -> of type text
				Allergies ->of type text
				Blood Pressure ->of type varchar = length 20
				Cholesterol Level -> of type varchar = length 20
				Date -> of type varchar = length 20
				
	      
   
   
