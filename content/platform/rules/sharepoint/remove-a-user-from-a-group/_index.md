---
title: "Remove a user from a group"
typora-root-url: ..\..\..\..\..\static
---

This rule allows you to remove a user from a SharePoint group using Kianda.

## When to use

This rule should be used when a user within Kianda should be removed from a SharePoint Group, for example, an employee leaving a company and to ensure they are removed from team groups.

You can add this rule:

- [x] to a field
- [x] to a form 
- [x] to a process (the rule will run on load)

## Before you get started

In advance of using the **Remove a user from a group** rule, you need to have created one or more forms in your process. In the forms you must have created two separate fields which are needed for:

- Field which will represent the **title** of the group you want to remove a user from, for example a **Text box** field. To learn more about how to create a text box field go to [Text box control](/platform/controls/input/textbox/).
- Field which will represent the **description** of the group, this can also be a text box field.

## How to use

To apply this rule, first choose an item to attach the rule to and have a SharePoint data source ready where you want the user to be removed from a group. This data source should be a predefined data connector created with **Data sources** under **Administration**. 

1. Select the field or other item to attach the rule to.

2. Click on **Add a rule** > **SharePoint** > **Remove a user from a group**.

3. In the **Edit rule - Remove a user from a group** dialog box, give the rule a **Title**. Then select a SharePoint data source from the drop-down list.

    ![Remove a user from a group dialog box](/images/remove-user-group-rule.jpg)

4. Two new fields will appear: **Username** and **Group name**. These are used to confirm the user which is to be removed and the group they are to be removed from. 
   For **Group title** **field**, select the field where the group title is stored for example, a list field.
   For **Username or User Id**, select the field where the Username or User id is stored.

5. Once these fields are set you can also set conditions for the rule, see [Conditions](/platform/rules/general/add-conditions/) for more information. 

6. The final two sections are optional: **On success mapping** and **Error mapping**. See [Success and Error Mapping](/platform/rules/general/success-error-mapping/) for more information. 

7. Click on **OK** when complete.

   

### User tip ![Target icon](/images/05.png) ###

If you have multiple rules attached to the field or other item, you may wish to reorder the rules to change the order of rule execution. Go to [Multiple rules](/platform/rules/general/multiple-rules/)  to find out more. 



## What's next  ![Idea icon](/images/18.png) ##

Now that you've learned about **Remove a user from a group**, return to the [SharePoint rules](/platform/rules/sharepoint/) page to find out about other SharePoint rules. 

   

   

   

