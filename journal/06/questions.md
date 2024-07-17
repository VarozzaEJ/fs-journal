# Single Page Applications with Vue
01. What is the entrypoint of an application?

  > The entrypoint of an application is where someone is directed the second they open a site or application.

02. What is the difference between a vue `component` and `page`?

  > Components split the defining parts of pages into seperate pieces, making it easier to read and put logic behind. Pages are the main components that display content to the screen.

03. What is ***Component-Based Architecture***?

  > Component based architecture is using components to not only make things easier to read but also easier to understand. It allows things to have easily defined purposes in your code. You could view them as building blocks, building on top of another.

04. What are the three tags that make up a Vue component?

  > The three tags are Script, Template, and Style

05. What are ***lifecycle hooks***? What are lifecycle hooks used for?

  > An example of a lifestyle hook is "OnMounted" which acts in the same way as a constructor, immediately running when an app is loaded.

06. Which component in Vue does the vue-router use to mount pages onto?

  > The Vue Router uses the loadPage function. It does so by string interpolating the name of the page you created inside of the file path.

07. What is the difference between the `AppState` and the state object within a component?

  > The state object within a component has a smaller scope: only allowing that component to see a variable declared within that component. On the other hand, the AppState allows for any file to look at variables declared within the AppState.

08. What is the responsibility of `Services` in our Vue projects?

  > Services have the same responsibility as with the regular MVC Pattern. They change data in the appState.

09. What are ***props*** and how are they used? Provide an example

  > Props stand for properties. An example of this is...FIXME

10. What is the Vue method used to create watchable objects such as `state` or `AppState`?

  > The method is ref()
