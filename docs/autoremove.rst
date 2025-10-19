Removing old packages
==================

For packages that are now redundant on your system, there is an easy and quick way to remove these redundant packages to save on disk space, among other benefits.

To remove redundant packages from your system, do the following:

1. Open Konsole (:menuselection:`Applications Menu --> System --> Konsole`)

2. Type ``pkexec apt autoremove`` and press :kbd:`Enter`

3. Authenticate through the authentication dialog that appears

4. Check the output specifying what packages will be removed from your system in case there are any packages you would like to keep installed

.. hint::
    If any packages you want to keep installed are listed there, type :kbd:`n` on the question, press :kbd:`Enter`, then type ``pkexec apt install (the package's name without brackets)`` and press :kbd:`Enter` again to mark that package as manually installed and disqualify it from future ``autoremove`` operations.

5. Once you're fine with everything ``autoremove`` wants to remove, type :kbd:`y` on the question and press :kbd:`Enter` to confirm the removal operations.

When the operation completes and returns you to green and blue text on the left of your input, you can close Konsole with the close button in its titlebar.