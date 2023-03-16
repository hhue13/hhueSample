# Snoop Application to test (and show) a WebSphere/Open Liberty deployment

Sample WAR applicaton to test a Liberty deployment and to reveal some WebSphere Liberty info.

The Application has been created based

- on the [OpenLiberty get started](https://openliberty.io/guides/maven-intro.html)
- on the following [SampleWebApp](https://github.com/AKSarav/SampleWebApp.git) which has been enhanced to display liberty information

# How to test your liberty deployment

Copy the .war file to the __`<server-dir>/dropins`__ directory and verify via the  that it got expanded correctly in the **`<server-dir>/apps/expaned`** directory of the server.

If the war is installed correctly you can see the URL to access the application in the **console.log** of the server.

The running application should show some snoop application like the following:

`![Sample output for snoop JSP](image/README/sampleOutput.png "`Sample output for snoop JSP`")`
