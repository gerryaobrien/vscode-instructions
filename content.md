#LAB1: Set up GitHub Copilot

##Objective

After completing this lab, you will be able to:

- Select a GitHub Copilot plan
- Install the GitHub Copilot extension in Visual Studio Code
- Manage GitHub Copilot Settings in Visual Studio Code
- Interact with GitHub Copilot code completion

**Estimate time to complete this lab**


60 minutes

##Scenario

As a software developer, you are tasked with evaluating older code. You will use GitHb Copilot to help you understand the codebase as you are not familiar with it. Installing and configuring the extension in Visual Studio Code will help you use AI to understand unfamiliar code. You will examine how to use GitHub Copilot for code completions and AI assistance.

TEST

	![Nap_Day.jpg](/media/Nap_Day.jpg)


# Exercise 1: GitHub Copilot Setup

**Objectives**

In this exercise, you will learn how to install GitHub Copilot extensions in Visual Studio Code.


1. [ ] Log on to @lab.VirtualMachine(Workstation1).SelectLink.

	Use the following credentials:  
	**Username**: +++Admin+++  
	**Password**: +++Passw0rd!+++  

1. [ ] Double-click the Visual Studio Code icon on the Desktop.

1. [ ] Select the Extensions icon on the Activity Bar.

1. [ ] In the Search Bar, type **GitHub Copilot**: +++GitHub Copilot+++.

1. [ ] Locate the extension in the list and select the **Install** button. This should install both GitHub Copilot and GitHub Copilot Chat extensions.

1. [ ] Once the extensions are installed, close and restart Visual Studio Code.

1. [ ] After Visual Studio Code restarts, select the Accounts icon in the Activity bar and sign in using your personal GitHub account to use the free version of GitHub Copilot.

1. [ ] Close the Welcome and Walkthrough tabs in the editor window.

# Exercise 2: Configure GitHub Copilot Completions

**Objectives**

- Configure the supported languages for Copilot to offer code completions for
- Choose a completions model

##Task 1

In this task you will configure the languages that you want Copilot to offer completions for.


1. [ ] Ensure that Visual Studio Code is open.

1. [ ] Select the **GitHub Copilot** icon next to the Search bar at the top of the VS Code window.

1. [ ] Select **Configure Code Completions** from the drop-down menu.

1. [ ] When the **Select an option** dialog opens, choose **Edit Settings**.

1. [ ] Take note that the first setting under **GitHub > Copilot: Advanced** should indicate that Copilot is enabled for all items. This is indicatedby the asterisk in the Item column and **true** in the Value column. Copilot is enabled for supported programming languages.

1. [ ] You can hover the mouse over the value of **false** for markdown. Select the pencil icon to enable editing of the setting.

1. [ ] Select the drop-down menu for **false** and change the value to **true**.

1. [ ] Select **OK** to apply the change. Copilot is now enabled for markdown files.

1. [ ] Selecting the **Add item** button allows you to enter a new key under the **Item** column and a value of true of false. This allows you to add Copilot completions for other languages. You must enter the language manually in the Item column.

1. [ ] Review the other settings but do not make any changes at this time.

## Task 2

In this task, you will learn to choose the completions model used by Copilot.

1. [ ] Select the **GitHub Copilot** icon next to the Search bar at the top of the VS Code window.

1. [ ] Select **Change Completions Model** from the drop-down menu.

1. [ ] The default model is GPT-4o Copilot. Select the **Learn more** option to open a web page to learn more about changing the completions model.

# Exercise 3: Interact with GitHub Copilot Code Completion

**Objectives**

- Use GitHub Copilot chat to evaluate code
- Use gitHub Copilot chat to suggest code completions
- Use Inline Chat to perform code completions

## Task 1

1. [ ] Open Visual Studio Code if not already open.

1. [ ] On the left nav pane, select the **Accounts** icon and then select Sign in to use Copilot.

1. [ ] Select **Sign in** in the dialog that pops up.

1. [ ] When the web browser opens, sign in to your GitHub account.

1. [ ]  When the **This site is trying to open Visual Studio Code.** dialog opens, select **Open**.

1. [ ] When Visual Studio Code finishes setting up GitHub Copilot, selec **Open Folder**.

1. [ ] Navigate to **E:\Allfiles** and open the **Extract_Entities** folder.

1. [ ] Select **Trust Publisher**.

1. [ ] Expand the **EXTRACT_ENTITIES** folder and select **Program.cs** to open it in the editor.

1. [ ] Open GitHub Copilot chat by selecting the Copilot icon in at the top of VS Code, or use the shortcut key combination of **Ctrl+Alt+I**.
