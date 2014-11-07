To install:

1.  Start MPIDE

2.  Look under File->Preferences and take note of your
    Sketchbook Location

3.  Shutdown MPIDE

4.  Under your Sketchbook directory create a subdirectory called
    "libraries"; this directory may already exist.

5.  Unzip the deIPcK.zip in the libraries directory.

6.  You should have 5 subdirectories added (DEIPcK, DEWFcK,
    IM8720PHY, MRF24G, HTTPServer).

    These are the Digilent Open Source Network Libraries
    and the HTTP Server library (Library needed to build the HTTP
    Example Server)

7.  Restart MPIDE

8.  In MPIDE You should see the new libraries under
    Sketch->Import Library, under Contributed.

9.  Also you should see under File->Examples the chipKIT library
    examples directories.

10. If you are looking for the PC side code for the examples,
    look under DEIPcK\examples\xxx\PCCode

11. If you are looking for the deIP HTTP Example server, look
    under DEWFcK\examples\deWebServer; Or in MPIDE under
    File->Examples->DEWFcK->deWebServer
