Advanced Usage
==============

Let's look at some advanced features of Barista.

Filtering apps by install source
--------------------------------

Most often, you will be testing your apps that will be installed locally (e.g., via adb). Thus, Barista shows only such apps.

However, if you installed the app from Google play and would like to see it in Barista, you can enable "Show Playstore Apps" in Settings.

You can also see System apps, which are default Android apps.


Using Dynamic Variables in Tests
--------------------------------

Often your app have dynamic text entries that need to be interacted with. For instance, if your app loads a list of news from a feed that you don't have control of, you might need to make your test handle such dynamic entries.

For this case, Barista provides a *"Store text in var"* option for TextViews.
This initializes a new variable with a name provided, and can be used later in
the test case.

Example usage:

* Open feed page
* Store ``text`` of first feed element
* Click on first element
* Ensure that the stored ``text`` appears on the page
