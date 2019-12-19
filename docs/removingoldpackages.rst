Removing old packages
==================

For packages that are now redundant on your system, there is an easy and quick way to remove these redundant packages to save on disk space, among other benefits. Currently there is no way through the Software Sources, however you can easily do this operation in a Terminal window.

To remove redundant packages from your system, do the following:

1. Open Terminal (:menuselection:`Applications Menu --> System / Administration --> Konsole / Terminal`)

2. Type ``pkexec apt autoremove`` and press :kbd:`Enter`

3. Authenticate through the authentication dialog that appears

4. Check the output specifying what packages will be removed from your system in case there are any packages you would like to keep installed

.. hint::
    If any packages you want to keep installed are listed there, type 'n' on the question, press :kbd:`Enter`, type ``pkexec apt install (the package's name goes here without brackets)`` and press :kbd:`Enter` again to mark that package as manually installed (makes the package immune to autoremove)

5. Once you're sure that everything the command wants to remove is fine on your terms to be removed, type 'y' on the question and press :kbd:`Enter` to confirm the package operations.

6. When you're taken back to the prompt, with green and blue text on the left of your input, close Konsole or Terminal as you're done.