---
title: demo
---

# demo title

build_entry_point: Indicate how to run the build. User can either use the build tool OP provides or use their own tools to build the content.
•git_repository_url_open_to_public_contributors - This URL would need to be defined if the above value is set to true. It can be the same Git repo if the whole project is public. It can also be a separated public repo for external contribution while keeing the internal repo private.
•docsets_to_publish: A collection of docsets that need to be published.◦docset_name - Provide the name of the docset. This docset need to provisioned on portal at first, otherwise the content under the docset won't be published.◾For different docsets the names should be different.
◾For docsets that are just different in locale or version, the name should be same. Otherwise, the fallback logic won't work.

◦build_output_subfolder - The relative output sub folder of the build tool. Content that has been built will be put there. Only content under that folder will be published. So this value depends on the build tools. 
◦version - Version of current content. Start from 0.
◦locale - Just leave it as 'en-us' as localized repos are created/configured using the .localization-config file. 
◦open_to_public_contributors◾Set to true if you want your customers to contribute to the content.
◾Set to false if you do not want your customers to contribute to the content.

◦type_mapping - As we can only build conceptual content right now, it should be "Conceptual": "Content".
◦branches_to_filter - You can exclude any branches from building. Recommended if people are new to Open Publishing to protect the "live" branch, so content does not get published by mistake. 
◦open_to_public_contributors - The value can be true or false. Here true means your content would accept community contribution, so there would be a button showing on the rendered page which directs external users to a repository to submit their pull requests. 

•notification_subscribers - Provide the email array of some ones who want to receive the notification. Separate each of the users or distribution lists by a comma. Example: "notification_subscribers": ["mayastmicrosoft.com", "yanzmicrosoft.com", "fenxumicrosoft.com"]
•branches_to_filter - Provide the branch array which will won't be monitored by OP build and publish. When teams are just testing and we are provisioning in production, we should filter out the "live" branch to prevent your branch will go live.


build_entry_point: Indicate how to run the build. User can either use the build tool OP provides or use their own tools to build the content.
•git_repository_url_open_to_public_contributors - This URL would need to be defined if the above value is set to true. It can be the same Git repo if the whole project is public. It can also be a separated public repo for external contribution while keeing the internal repo private.
•docsets_to_publish: A collection of docsets that need to be published.◦docset_name - Provide the name of the docset. This docset need to provisioned on portal at first, otherwise the content under the docset won't be published.◾For different docsets the names should be different.
◾For docsets that are just different in locale or version, the name should be same. Otherwise, the fallback logic won't work.

◦build_output_subfolder - The relative output sub folder of the build tool. Content that has been built will be put there. Only content under that folder will be published. So this value depends on the build tools. 
◦version - Version of current content. Start from 0.
◦locale - Just leave it as 'en-us' as localized repos are created/configured using the .localization-config file. 
◦open_to_public_contributors◾Set to true if you want your customers to contribute to the content.
◾Set to false if you do not want your customers to contribute to the content.

◦type_mapping - As we can only build conceptual content right now, it should be "Conceptual": "Content".
◦branches_to_filter - You can exclude any branches from building. Recommended if people are new to Open Publishing to protect the "live" branch, so content does not get published by mistake. 
◦open_to_public_contributors - The value can be true or false. Here true means your content would accept community contribution, so there would be a button showing on the rendered page which directs external users to a repository to submit their pull requests. 

•notification_subscribers - Provide the email array of some ones who want to receive the notification. Separate each of the users or distribution lists by a comma. Example: "notification_subscribers": ["mayastmicrosoft.com", "yanzmicrosoft.com", "fenxumicrosoft.com"]
•branches_to_filter - Provide the branch array which will won't be monitored by OP build and publish. When teams are just testing and we are provisioning in production, we should filter out the "live" branch to prevent your branch will go live.


hello.
