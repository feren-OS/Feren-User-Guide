AppImages
==================

.. warning::
    AppImages are a bad idea for Feren OS security. Be careful with what AppImages you use and where you get them from. I, The Feren OS Developer, take no responsibility for any damage a malicious AppImage file might cause.
    
    Only authenticate AppImage applications to do stuff as Superuser if they're from a trusted source and if THEY show the authentication dialog themselves.

What are AppImages?
----------------

AppImages are applications packaged in an executable file that are designed to be directly ran from the ".AppImage" file you download them as. Users of macOS will be very familiar with the concept of AppImages as macOS applications are packaged in a very similar way.

As such, they provide the simplicity of macOS applications and Windows "EXE" files that just work when you run them on Feren OS and other Linux distributions.

To run an AppImage, simply right-click it, select :guilabel:`Properties`, go to the :guilabel:`Permissions` tab and make sure :guilabel:`Allow executing file as program` is ticked. Then close the Properties window and open up the file as if it was any other file. Before you know it, the application in the file you just opened is now running.