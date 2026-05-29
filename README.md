# Windows Event Viewer Filters
A collection of useful filters to import and use in Windows 11's Event Viewer program.

## Adding a Filter View

1. Right-click on **Custom Views** folder.
2. Left-click **Create Custom View...**.
3. Swap to the **XML** tab.
4. Tick the **Edit query manually** checkbox.
5. Click **Yes** on the popup warning.
6. Copy and paste the `*.xml` filter you wish to use in the UI box.
> [!NOTE]
> Be aware that comments are removed and styling is automatically applied in the Event Viewer UI after pasting your XML script.
7. Finalize by clicking **OK** in the bottom-right of the **Create Custom View** window.

You should now see your new Custom View. Feel free to add further filters or tweak existing ones.
