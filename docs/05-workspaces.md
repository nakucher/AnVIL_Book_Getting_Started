# (PART\*) Working on AnVIL {-}

# Workspaces

Workspaces are the building blocks of projects in Terra. Inside a Workspace, you can run analyses, launch interactive tools like RStudio and Galaxy, store data, and share results. 

To get a Workspace of your own, you can

- **Clone a Workspace**: Cloning an existing Workspace allows you to copy existing documentation, code, and/or data into your own experimental space.
- **Create a Workspace**: Creating a new Workspace from scratch allows you to fully customize the contents.

The video below gives a brief introduction to the parts of a Workspace.

<iframe src="https://drive.google.com/file/d/18WUmQfDnulHdaMlrH0Eh6kwIP3zTkaqp/preview" width="640" height="360" allow="autoplay"></iframe>

## Access Your Workspaces

If you are part of a research team, you may have been added to some existing Workspaces.  To find and access your Workspaces, follow the steps below.



1. [Launch Terra](https://anvil.terra.bio/#workspaces)

1. In the drop-down menu on the left, navigate to "Workspaces". Click the triple bar in the top left corner to access the menu. Click "Workspaces".

    <img src="05-workspaces_files/figure-html//1ioYY0n3CcrP934WRKEsQ1aKocPqfswdWWHxYCf76BCg_g10f3888d99c_0_156.png" title="Screenshot of Terra drop-down menu.  The &quot;hamburger&quot; button to extend the drop-down menu is highlighted, and the menu item &quot;Workspaces&quot; is highlighted." alt="Screenshot of Terra drop-down menu.  The &quot;hamburger&quot; button to extend the drop-down menu is highlighted, and the menu item &quot;Workspaces&quot; is highlighted." width="480" />

1. You are automatically directed to the "My Workspaces" tab.  Here you can see any Workspaces that have been shared with you, along with your permission level.

    <img src="05-workspaces_files/figure-html//1ioYY0n3CcrP934WRKEsQ1aKocPqfswdWWHxYCf76BCg_g10f3888d99c_0_0.png" title="Screenshot of Terra Workspaces page with the &quot;My Workspaces&quot; tab selected.  The &quot;My Workspaces&quot; tab and the column showing permission level are highlighted." alt="Screenshot of Terra Workspaces page with the &quot;My Workspaces&quot; tab selected.  The &quot;My Workspaces&quot; tab and the column showing permission level are highlighted." width="480" />
   
    - **Reader** means you can open the Workspace and see everything, but can't do any computations or make any edits.
    - **Writer** means you can run computations, which will charge costs to the Workspace's Billing Project.  Writers can also make edits to the Workspace.
    - **Owner** is similar to Writer, but also allows you to control who can access the Workspace.
    
1. Click on the name of a Workspace to open it.  Opening and viewing a Workspace does not cost anything.

    <img src="05-workspaces_files/figure-html//1ioYY0n3CcrP934WRKEsQ1aKocPqfswdWWHxYCf76BCg_g10f3888d99c_0_163.png" title="Screenshot of Terra Workspaces page with the &quot;My Workspaces&quot; tab selected.  The name of one of the Workspaces is highlighted." alt="Screenshot of Terra Workspaces page with the &quot;My Workspaces&quot; tab selected.  The name of one of the Workspaces is highlighted." width="480" />

1. When you open a Workspace, you are directed to the Workspace Dashboard.  This generally has a description of the Workspace contents, as well as some useful details about the Workspace itself.

    <img src="05-workspaces_files/figure-html//1ioYY0n3CcrP934WRKEsQ1aKocPqfswdWWHxYCf76BCg_g10f3888d99c_0_170.png" title="Screenshot of a Terra Workspace.  The &quot;Dashboard&quot; is highlighted." alt="Screenshot of a Terra Workspace.  The &quot;Dashboard&quot; is highlighted." width="480" />

From here you can navigate through the different tabs of the Workspace, and if you have sufficient permission, you can start running analyses.  If you are only a Reader, you may need to "clone" (make your own copy) of the Workspace before you can start working.

## Clone an Existing Workspace {#clone-workspace}

Cloning an existing Workspace allows you to copy existing documentation, code, and/or data into your own experimental space.

Cloning creates a new copy of the Workspace that will charge costs to the Billing Project of your choice. Note that you can only clone a Workspace if you are at least a "User" on the Terra Billing Project.  This helps prevent unwanted charges.  Workspaces charge money to their associated Billing Project, regardless of who conducts the activity, so it's important to be careful about who has permission to use the Workspace (see [Add Members to Workspace] for details).

If you need to clone a Workspace but don't have permission to create your own Workspaces, contact your PI or lab manager so that they can either grant you permission or clone the Workspace for you.

The following steps show you how to clone a Workspace that has already been developed by other AnVIL users. When cloning, AnVIL makes a copy of notebooks and code for you to modify. Data however, is linked back to the original Workspace through Data Tables, which saves space!


1. [Launch Terra](https://anvil.terra.bio/#workspaces)

1. Locate the Workspace you want to clone. If a Workspace has been shared with you ahead of time, it will appear in "MY WORKSPACES". You can clone a Workspace that was shared with you to perform your own analyses. In the screenshot below, no Workspaces have been shared.

    <img src="05-workspaces_files/figure-html//1JvfOluHe543cUCyyH3zz0ew-1J1QjhdYGZufW9NrC_M_g117abafa453_0_0.png" title="Screenshot of Terra &quot;MY WORKSPACES&quot; menu. The &quot;MY WORKSPACES&quot; tab is highlighted. No Workspaces are visible because none have been shared with the user. There is an option to create a new Workspace." alt="Screenshot of Terra &quot;MY WORKSPACES&quot; menu. The &quot;MY WORKSPACES&quot; tab is highlighted. No Workspaces are visible because none have been shared with the user. There is an option to create a new Workspace." width="480" />

1. If a Workspace hasn't been shared with you, navigate to the "FEATURED" or "PUBLIC" Workspace tabs.

    <img src="05-workspaces_files/figure-html//1JvfOluHe543cUCyyH3zz0ew-1J1QjhdYGZufW9NrC_M_g117abafa453_0_144.png" title="Screenshot of Terra &quot;My Workspaces&quot; menu. The &quot;FEATURED&quot; tab is highlighted." alt="Screenshot of Terra &quot;My Workspaces&quot; menu. The &quot;FEATURED&quot; tab is highlighted." width="480" />
    
1. Use the search box to find the Workspace you want to clone.

    <img src="05-workspaces_files/figure-html//1JvfOluHe543cUCyyH3zz0ew-1J1QjhdYGZufW9NrC_M_g117abafa453_0_288.png" title="Screenshot of Terra &quot;My Workspaces&quot; menu. The search bar is highlighted and the user has typed in the term &quot;COVID-19&quot;. A Workspace related to COVID-19 appears in the results." alt="Screenshot of Terra &quot;My Workspaces&quot; menu. The search bar is highlighted and the user has typed in the term &quot;COVID-19&quot;. A Workspace related to COVID-19 appears in the results." width="480" />
    
1. Click the teardrop button on the far right next to the Workspace you want to clone. Click "Clone". You can also clone the Workspace from the Workspace Dashboard instead of the search results.

    <img src="05-workspaces_files/figure-html//1JvfOluHe543cUCyyH3zz0ew-1J1QjhdYGZufW9NrC_M_g117abafa453_0_432.png" title="Screenshot of Terra &quot;My Workspaces&quot; menu with the Workspace that we want to clone. The teardrop button has been clicked to bring up the options. The &quot;Clone&quot; option from the list is highlighted." alt="Screenshot of Terra &quot;My Workspaces&quot; menu with the Workspace that we want to clone. The teardrop button has been clicked to bring up the options. The &quot;Clone&quot; option from the list is highlighted." width="480" />
    <img src="05-workspaces_files/figure-html//1JvfOluHe543cUCyyH3zz0ew-1J1QjhdYGZufW9NrC_M_g117abafa453_0_577.png" title="Screenshot of the Dashboard for the Workspace that we want to clone. The teardrop button has been clicked to bring up the options. The &quot;Clone&quot; option from the list is highlighted." alt="Screenshot of the Dashboard for the Workspace that we want to clone. The teardrop button has been clicked to bring up the options. The &quot;Clone&quot; option from the list is highlighted." width="480" />
    
1. You will see a popup box appear. Name your Workspace and select the appropriate Terra Billing Project.  **All activity in the Workspace will be charged to this Billing Project** (regardless of who conducted it). Remember that each Workspace should have its own Billing Project.

    <img src="05-workspaces_files/figure-html//1JvfOluHe543cUCyyH3zz0ew-1J1QjhdYGZufW9NrC_M_g117abafa453_0_722.png" title="Screenshot of the &quot;clone workspace&quot; Terra popup dialog box. The Workspace name and Billing Project dropdown are highlighted. Text has been filled in for the Workspace name as &quot;Lab-member-1-workspace-2&quot;." alt="Screenshot of the &quot;clone workspace&quot; Terra popup dialog box. The Workspace name and Billing Project dropdown are highlighted. Text has been filled in for the Workspace name as &quot;Lab-member-1-workspace-2&quot;." width="480" />

1. If you are working with protected data, you can set the **Authorization Domain** to limit who can be added to your Workspace.  Note that the Authorization Domain cannot be changed after the Workspace is created (i.e. there is no way to make this Workspace shareable with a larger audience in the future).  Workspaces by default are only visible to people you specifically share them with.  Authorization domains add an extra layer of enforcement over privacy, but by nature make sharing more complicated.  We recommend using Authorization Domains in cases where it is extremely important and/or legally required that the data be kept private (e.g. protected patient data, industry data).  For data you would merely prefer not be shared with the world, we recommend relying on standard Workspace sharing permissions rather than Authorization Domains, as Authorization Domains can make future collaborations, publications, or other sharing complicated.

    <img src="05-workspaces_files/figure-html//1JvfOluHe543cUCyyH3zz0ew-1J1QjhdYGZufW9NrC_M_g117abafa453_0_867.png" title="Screenshot of Terra popup dialog box for creating a new Workspace. The drop-down menu labeled &quot;Authorization domain&quot; is highlighted." alt="Screenshot of Terra popup dialog box for creating a new Workspace. The drop-down menu labeled &quot;Authorization domain&quot; is highlighted." width="480" />
    
1. Click "CLONE WORKSPACE".  The new Workspace should now show up under your Workspaces.

    <img src="05-workspaces_files/figure-html//1JvfOluHe543cUCyyH3zz0ew-1J1QjhdYGZufW9NrC_M_g117abafa453_0_1012.png" title="Screenshot of Terra popup dialog box for creating a new Workspace. The &quot;Clone Workspace&quot; button is highlighted." alt="Screenshot of Terra popup dialog box for creating a new Workspace. The &quot;Clone Workspace&quot; button is highlighted." width="480" />

## Create a New Workspace

Creating a new Workspace from scratch allows you to fully customize the contents.

Note that you can only create a new Workspace if you are at least a "User" on a Terra Billing Project.  This helps prevent unwanted charges.  Workspaces charge money to their associated Billing Project, regardless of who conducts the activity, so it's important to be careful about who has permission to use the Workspace (see [Add Members to Workspace] for details).

If you need to create a Workspace but don't have permission, contact your PI or lab manager so that they can either grant you permission or create the Workspace for you.

The following steps show you how to create a Workspace so you can get started.


1. [Launch Terra](https://anvil.terra.bio/#workspaces)

1. In the drop-down menu on the left, navigate to "Workspaces". Click the triple bar in the top left corner to access the menu. Click "Workspaces".

    <img src="05-workspaces_files/figure-html//1zyqZHITAthNhXeH2XQqA7FMOu2mek6wfgGEaje1KQsk_g117989bd49c_0_150.png" title="Screenshot of Terra drop-down menu.  The &quot;hamburger&quot; button to extend the drop-down menu is highlighted, and the menu item &quot;Workspaces&quot; is highlighted." alt="Screenshot of Terra drop-down menu.  The &quot;hamburger&quot; button to extend the drop-down menu is highlighted, and the menu item &quot;Workspaces&quot; is highlighted." width="480" />

1. Click on the **plus icon** near the top of left of the page.

    <img src="05-workspaces_files/figure-html//1zyqZHITAthNhXeH2XQqA7FMOu2mek6wfgGEaje1KQsk_g117989bd49c_0_733.png" title="Screenshot of Terra Workspaces page.  The &quot;+&quot; is highlighted." alt="Screenshot of Terra Workspaces page.  The &quot;+&quot; is highlighted." width="480" />

1. Name your Workspace and select the appropriate Billing Project.  **All activity in the Workspace will be charged to this Billing Project** (regardless of who conducted it).

    <img src="05-workspaces_files/figure-html//1zyqZHITAthNhXeH2XQqA7FMOu2mek6wfgGEaje1KQsk_g117989bd49c_0_877.png" title="Screenshot of Terra dialog box for creating a new Workspace.  The text box labeled &quot;Workspace name&quot; and the drop-down menu labeled &quot;Billing project&quot; are highlighted." alt="Screenshot of Terra dialog box for creating a new Workspace.  The text box labeled &quot;Workspace name&quot; and the drop-down menu labeled &quot;Billing project&quot; are highlighted." width="480" />

1. If you are working with protected data, you can set the **Authorization Domain** to limit who can be added to your Workspace.  Note that the Authorization Domain cannot be changed after the Workspace is created (i.e. there is no way to make this Workspace shareable with a larger audience in the future).  Workspaces by default are only visible to people you specifically share them with.  Authorization domains add an extra layer of enforcement over privacy, but by nature make sharing more complicated.  We recommend using Authorization Domains in cases where it is extremely important and/or legally required that the data be kept private (e.g. protected patient data, industry data).  For data you would merely prefer not be shared with the world, we recommend relying on standard Workspace sharing permissions rather than Authorization Domains, as Authorization Domains can make future collaborations, publications, or other sharing complicated.

    <img src="05-workspaces_files/figure-html//1zyqZHITAthNhXeH2XQqA7FMOu2mek6wfgGEaje1KQsk_g117989bd49c_0_1022.png" title="Screenshot of Terra dialog box for creating a new Workspace.  The drop-down menu labeled &quot;Authorization domain&quot; is highlighted." alt="Screenshot of Terra dialog box for creating a new Workspace.  The drop-down menu labeled &quot;Authorization domain&quot; is highlighted." width="480" />

1. Click "CREATE WORKSPACE".  The new Workspace should now show up under your Workspaces.

    <img src="05-workspaces_files/figure-html//1zyqZHITAthNhXeH2XQqA7FMOu2mek6wfgGEaje1KQsk_g117989bd49c_0_1166.png" title="Screenshot of Terra dialog box for creating a new Workspace.  The &quot;Create Workspace&quot; button is highlighted." alt="Screenshot of Terra dialog box for creating a new Workspace.  The &quot;Create Workspace&quot; button is highlighted." width="480" />

## Add Members to Workspace

Members can be added to a Workspace with a few different permission levels:

<img src="05-workspaces_files/figure-html//1hhdPNfuAhbwkl5LlNVlJiCIx_rbzVp3jSJJeksqiR5I_g117dd5f15db_0_584.png" title="Table summarizing Workspace permission levels." alt="Table summarizing Workspace permission levels." width="480" />

More details about the permissions associated with each Access Level can be found in the [Terra documentation](https://support.terra.bio/hc/en-us/articles/360025851892-Reader-writer-or-owner-Workspace-access-controls-explained).

Managing permissions for a Workspace has important implications:

- **Billing**: Terra charges are associated with Workspaces rather than users.  Any billable activity that takes place in a given Workspace will be charged to the associated Billing Project, regardless of who conducted the activity.  If there are multiple users with permission to compute, it is impossible to tell who conducted the activity.
- **Data access**: Especially when working with protected data, it’s important to ensure that users have proper authorization to view the data before giving them access to a Workspace containing the data.  Terra provides **Authorization Domains** to assist with this.

Make sure you understand what permissions you are granting before adding someone to your Workspace.

To add a member to a Workspace:


1. [Launch Terra](https://anvil.terra.bio/#workspaces)

1. In the drop-down menu on the left, navigate to "Workspaces". Click the triple bar in the top left corner to access the menu. Click "Workspaces".

    <img src="05-workspaces_files/figure-html//1hhdPNfuAhbwkl5LlNVlJiCIx_rbzVp3jSJJeksqiR5I_g117989bd49c_0_150.png" title="Screenshot of Terra drop-down menu.  The &quot;hamburger&quot; button to extend the drop-down menu is highlighted, and the menu item &quot;Workspaces&quot; is highlighted." alt="Screenshot of Terra drop-down menu.  The &quot;hamburger&quot; button to extend the drop-down menu is highlighted, and the menu item &quot;Workspaces&quot; is highlighted." width="480" />

1. Click on the name of the Workspace to open the Workspace. Opening a Workspace does not cost anything.  Certain activities in the Workspace (such as running an analysis) will charge to the Workspace’s Billing Project.  Workspace management (e.g. adding and removing members, editing the description) does not cost money.

    <img src="05-workspaces_files/figure-html//1hhdPNfuAhbwkl5LlNVlJiCIx_rbzVp3jSJJeksqiR5I_g117dd5f15db_0_289.png" title="Screenshot of Terra Workspace page.  The name of a Workspace is highlighted." alt="Screenshot of Terra Workspace page.  The name of a Workspace is highlighted." width="480" />

1. Click the circle with 3 dots on the right hand side to open the Workspace management menu.  Click "Share"

    <img src="05-workspaces_files/figure-html//1hhdPNfuAhbwkl5LlNVlJiCIx_rbzVp3jSJJeksqiR5I_g117dd5f15db_0_295.png" title="Screenshot of an individual Terra Workspace dashboard page.  The button for extending the Workspaces's drop-down menu is highlighted, and the menu item &quot;Share&quot; is highlighted." alt="Screenshot of an individual Terra Workspace dashboard page.  The button for extending the Workspaces's drop-down menu is highlighted, and the menu item &quot;Share&quot; is highlighted." width="480" />

1. Enter the email address of the user you want to share the Workspace with.  This must be the address associated with the account they are using to access Terra.

    <img src="05-workspaces_files/figure-html//1hhdPNfuAhbwkl5LlNVlJiCIx_rbzVp3jSJJeksqiR5I_g117dd5f15db_0_440.png" title="Screenshot of the dialog box for sharing a Terra Workspace.  The text box labeled &quot;User email&quot; is highlighted." alt="Screenshot of the dialog box for sharing a Terra Workspace.  The text box labeled &quot;User email&quot; is highlighted." width="480" />

1. Choose their permission level.

    - Remember that all activity in the Workspace will be charged to the Workspace's Billing Project, regardless of who conducts it, so only add members as "Writers" or "Owners" if they should be charging to the Workspace's Billing Project.
    - "Readers" can view all parts of the Workspace but cannot make edits or run analyses (i.e. they cannot spend money).  They can also clone their own copy of the Workspace where they can conduct activity on their own Billing Project.

    <img src="05-workspaces_files/figure-html//1hhdPNfuAhbwkl5LlNVlJiCIx_rbzVp3jSJJeksqiR5I_g117dd5f15db_0_756.png" title="Screenshot of the dialog box for sharing a Terra Workspace.  The drop-down menu labeled with the email of the user you are sharing with is highlighted and the menu item &quot;Writer&quot; is selected." alt="Screenshot of the dialog box for sharing a Terra Workspace.  The drop-down menu labeled with the email of the user you are sharing with is highlighted and the menu item &quot;Writer&quot; is selected." width="480" />

1. Click "Save".  The user should now be able to see the Workspace when logged in to Terra.

    <img src="05-workspaces_files/figure-html//1hhdPNfuAhbwkl5LlNVlJiCIx_rbzVp3jSJJeksqiR5I_g117dd5f15db_0_902.png" title="Screenshot of the dialog box for sharing a Terra Workspace.  The &quot;Save&quot; button is highlighted." alt="Screenshot of the dialog box for sharing a Terra Workspace.  The &quot;Save&quot; button is highlighted." width="480" />
