---
summary: Extend your app with public elements to make your app do more for your users.
tags:
locale: en-us
guid: 7ae0d274-cced-49dc-8a2f-0c3116db74f7
app_type: mobile apps, reactive web apps
---

# Use public elements

You can use public elements to extend the capabilities of your app. Public elements are elements [shared by members of your organization](../reuse-elements.md#public-elements) or packaged into libraries that come bundled with Project Neo.

For example, you can use elements in the HTTP library to extend your app to handle HTTP requests and responses. The HTTP library comes bundled with Project Neo.

## Add public elements

To use public elements, you must first add them to your app. Navigate to the **Add public elements** icon on the top toolbar of Service Studio or use the **Ctrl+Q** shortcut. In the selection window, you can filter by name, description, and type of element. Select the element or elements you want to add and click **Add**.

### Libraries

Project Neo elevates libraries to a top-level concept. Libraries exist at the same level as apps, and they have their own lifecycle.

You can build you own libraries, but there are many provided by OutSystems available out of the box. You can find a list of currently available libraries in the [reference documentation](../../reference/intro.md#libraries).

When you add a public element from a provided library, it becomes available to use as an action in the **Server Actions** folder of the **Logic** tab. You can use an action in the logic flow of any server action or service action.

The public element may also be available as function in the **User Functions** folder of the expression editor. You can use a function in the logic flow any expression of any server action or service action. You can check if an action is available as a function in the [reference documentation](../../reference/intro.md#libraries).

The functions available in provided libraries complement the built-in functions available in the **Built-in Functions** folder of the expression editor.