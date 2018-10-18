---
description: Steps that describe how to create rules in Dynamic Tag Management.
keywords: Dynamic Tag Management;rule;create rule;new rule;event-based rule;page load rule;direct call rule
seo-description: Steps that describe how to create rules in Dynamic Tag Management.
seo-title: Create new rule
solution: Marketing Cloud,Analytics,Target,Dynamic Tag Management
title: Create new rule
uuid: fd61b244-1bdd-446a-a659-6987a1514b80
index: y
internal: n
snippet: y
---

# Create new rule

Steps that describe how to create rules in Dynamic Tag Management.

1. [Create Web Property](../../c_implement-with-dtm/t_create-web-property.md#task_960467FBB7A54499AC228CB3AA3C4123), if you haven't done so already.
1. In the web property, click the **[!UICONTROL Rules]** tab.
1. Select the type of rule you wish to create from the left navigation pane, such as Event Based Rules or Page Load Rules.
1. Click **[!UICONTROL Create New Rule]**.
1. Name the rule and select a category, if you wish.
1. Next, set up the condition(s) for the rule. The setup differs depending on the type of rule you are implementing.

       | **Event-based rule** | [Create conditions for event-based rules](../../c_implement-with-dtm/c_rules/t_rules-event-conditions.md#task_A122DE72110F4579A91F9D96D92D39FC)  |
       |---|---|
       | **Page Load rule** | [Create conditions for page-load rules](../../c_implement-with-dtm/c_rules/t_rules-page-conditions.md#task_69B41CB230EE4530A755D91233F73706)  |
       | **Direct Call rule** | [Create conditions for direct-call rules](../../c_implement-with-dtm/c_rules/t_rules-direct-conditions.md#task_85EB8F01775A402BA53B8298F0AADA09)  |

   The category field is only for your own organizational purposes and is not required. You can delete categories by clicking the x icon in the category. 
1. [Set up actions for the condition to trigger](../../c_implement-with-dtm/c_rules/t_rules-actions.md#task_94DFE0D8B53A43E2892851BABE381121).