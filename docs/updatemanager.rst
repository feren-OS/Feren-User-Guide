Update Manager
==================

What is Update Manager?
----------------

Update Manager is a utility built into Feren OS that allows you to manually install updates. It's the place to go to if there is any updates available for Feren OS if you don't want to wait for Feren OS to automatically install updates.

.. hint::
    Feren OS installs available updates daily automatically by default from the default set of repositories included in Feren OS. Packages from extra repositories you've added will not get automatically updated by default.

.. figure:: images/updatemanager.png
    :width: 500px
    :align: center

    Update Manager

To install available updates in Update Manager, click on :guilabel:`Install Updates`.

To check for updates, click on :guilabel:`Refresh`.

To select all the available updates so that they get installed when you click on :guilabel:`Install Updates`.

To select none of the available updates click on :guilabel:`Clear`.

Extra Options
-------------------------------------

There are also multiple other options in Update Manager in the menubar.

In the :guilabel:`Edit` menu you can find :guilabel:`Preferences` to change some Update Manager settings, :guilabel:`System Snapshots` to launch Timeshift and :guilabel:`Software Sources` to launch Software Sources.

In the :guilabel:`View` menu you can toggle visible columns, toggle descriptions for updatable packages, show your system's update history, manage Linux Kernels and view Update Manager window information.

In the :guilabel:`Help` menu you can view the first login page in Update Manager, view Keyboard Shortcuts, view Help contents and view the Update Manager About dialog.

Disabling Automatic Updates
-------------------------------------

.. warning::
    Disabling automatic updates is not recommended.
    
.. hint::
    A future update to Update Manager will eventually add an easier way to toggle automatic updates in Update Manager preferences. At that point this guide will be updated to reflect this.

If you don't want automatic updates to occur on a daily basis, you can easily disable it through a user with administrator privilleges.

To start off, you will want to edit ``/etc/apt/apt.conf.d/10periodic``. In Feren OS you just need to open this file in Kate, and you will find it through Files at :menuselection:`File System --> etc --> apt --> apt.conf.d --> 10periodic`.

In Feren OS Classic, however, you will need to open a text editor as Superuser. An easy way to do this is to go into the Terminal and run this command: ``sudo xed /etc/apt/apt.conf.d/10periodic``

You should find a line saying ``APT::Periodic::Update-Package-Lists "1";``. Change the ``1`` to a ``0`` and save the document. Once the document is saved and the line is now saying ``APT::Periodic::Update-Package-Lists "0";`` restart and automatic updates should now be disabled.

.. hint::
    If the file doesn't yet exist, write that line in and save the file anew.