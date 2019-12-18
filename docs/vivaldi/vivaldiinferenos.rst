Using Vivaldi in Feren OS
==================

Using Vivaldi
----------------

Using Vivaldi in Feren OS is quite simple. If you have used Vivaldi before, you'll already know where everything is, however if you do not then here is a brief tour of Vivaldi:

.. figure:: images/vivaldidiagramen.png
    :width: 500px
    :align: center

    Vivaldi in Feren OS

If you need help with Vivaldi, don't forget to click the Vivaldi icon on the sidebar on the left of the window to open up the official help guide on Vivaldi.

Configuring the Feren OS Start Page
---------------

Feren OS uses a custom Start Page website by default as Vivaldi's New Tab Page. To configure the Start Page, click the cog on the top-right of the Start Page.

Once there, here is what each setting currently does:

* Background Image: Changes the background image used on the Start Page
* Hide elements of Start Page: Toggle on/off whether to hide the tiles under the search bar on the Start Page, the Feren OS Blog and Twitter panels below that or the credits. You can even hide them all to change the Start Page to an alternative layout based on its original layout before it gained the other items below the search bar.

.. hint::
    Due to security reasons the Start Page cannot take links to local files on your computer for the Start Page background - the background will just be black

Alternatively, you can also change the Start Page back to Vivaldi's own one, if you so desire. To change the Start Page back to Vivaldi's own, do the following:

1. Click the Vivaldi Settings (⚙) icon on the bottom-left of Vivaldi

2. Under :guilabel:`Homepage` select "Start Page"

3. Go into :guilabel:`Tabs`

4. Under :guilabel:`New Tab Page` select "Start Page"

If you want to go back to the Feren OS Start Page at any time just undo the changes you made here. In case you lose the address it is at https://feren-os.github.io/start-page.


Using the unmodified Vivaldi experience
---------------

If you are a purist or just want to use Vivaldi without any of the changes made in Feren OS, you can easily get an unmodified Vivaldi up and running with these steps:

1. Click the person icon on the top-right

2. Click :guilabel:`Manage People...` in the menu that appears

3. Click :guilabel:`Add Person` twice

4. A new Vivaldi window will pop up. Close the previous Vivaldi window

5. In this new Vivaldi window click the person icon on the top-right again

6. Click :guilabel:`Manage People...` again

7. Click :guilabel:`Person 1` (or whatever you named the old profile if you changed its name)

8. Click :guilabel:`Remove Person`

.. warning::
    Once you remove "Person 1", this operation cannot be undone without completely reimporting the Vivaldi configuration folder from /etc/skel manually which will completely reset Vivaldi back to the state it is initially in in Feren OS.


Changes in Feren OS to Vivaldi
----------------

Feren OS has a few changes made to Vivaldi by default to improve on its user experience for newcomers and to integrate the browser better in Feren OS by default.

These changes are mostly just cosmetic, however they might as well get mentioned here:

* The titlebar buttons were changed to be akin to the default Feren OS titlebar theme
* 7 new themes are added in Vivaldi: "Edgy", "Ow", "Who Turned The Lights Out?", "Classic", "Classic Dark", "Feren OS (Default)" and "Feren OS Dark"
* The theme used was changed to "Feren OS (Default)"
* The homepage was changed to https://feren-os.github.io/start-page
* "Show Exit Confirmation Dialog" was disabled
* "Show Close Window Confirmation Dialog" was disabled
* The Start Page background image was changed
* Speed Dial Appearance was set to "Show Title when Needed"
* New Tab Page was set to "Homepage"
* "Remove Tab Spacing in Maximized Windows" was enabled
* "Dim Icon when Hibernated" was enabled
* Page Load Progress was set to "Favicon Spinner"
* "Show Search Field in Address Bar" was disabled
* Three Web Panels were added: Vivaldi Help, Feren OS on Medium and Feren OS on Social Media