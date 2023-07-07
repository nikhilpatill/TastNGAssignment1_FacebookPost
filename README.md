# facebook-Assignment



<b>facebook-Assignment </b>

Completed with selenium + testng, Tested on Chrome, firefox , as maven project

How to run it (<b>run framwork </b> )<ul> <li> execution.bat </li> <li> cmd </li> <li> Maven test  </li> <li> Run textng.xml   </li>    </ul>   

Add Dependency to with version (<b>POM.xml </b> )


<ul>
    <li>java jdk 17 java.version 17 </li> 
	<li><artifactId>selenium-java</artifactId> <version>4.8.1</version>  </li>
	<li>
	<artifactId>webdrivermanager</artifactId>
	<version>5.3.2</version>
	</li>
    <li>	<groupId>org.apache.poi</groupId>
			<artifactId>poi</artifactId>
			<version>5.2.3</version>
	</li>	
	<li>  <artifactId>testng</artifactId>
			<version>7.7.1</version>
			<scope>test</scope>
	</li> 

	

	  <plugin>
					<artifactId>maven-surefire-plugin</artifactId>
					<version>3.0.0-M7</version>

					<configuration>
						<suiteXmlFiles>
							<!-- TestNG suite XML files -->

							<suiteXmlFile>testng.xml</suiteXmlFile>

							<!--	 <suiteXmlFile>${suiteXmlFile}</suiteXmlFile> -->
						</suiteXmlFiles>
					</configuration>


				</plugin>

	

   
		

</ul> 

<ul>

<li> <b> USE page object model use support pagefactory <b> </li>
<li><b> USE Eclipse ide </b> </li>
<li> <b> USE TestNG.xml file Add Suite, Test, , class , Method , Create suite </b>  <li>
<li> <b>USE Pages objcet model Facebook Assignment<b> </li>
<li> Pages add WebElement Initalization (@FindBy),(contructor),(Action Method ) <br> Test add testcase </li>
<li> Make it own Utility packages , As per need called method  Ex Action , property, Baseutility, DropDown, Wait,  </li>

</ul>


