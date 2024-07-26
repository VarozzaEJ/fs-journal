# Managing the Fullstack Application

1. Describe the two ways to bind Data in Vue?

  > The two ways to bind data to something and make it reactive are 'v-bind' and ':'

2. The `SPA` acronym stands for what?

  > Single Page Application

3. What are some of the advantages/uses of a `SPA` over a traditional one?

  > It is easier to load things because there is less load on the network.

4. What does the `onMounted` method in Vue do?

  > Runs a callback function when the page is loaded.

5. What is the `v-model` attribute in Vue for, and when might you use it?

  > v-model is used in forms to bind the data inside of each input to a variable with editable data.

6. What is the package.json file used for?

  > Package.json is a file that is loaded when a file is made to install dependencies into a file.

7. Which Vue attributes(directives) could you use to conditionally render elements on a page?

  > v-if and v-else

8. What is the purpose of the `key` attribute when using `v-for` on an element?

  > the key gives each instance of the v-for a unique identifier to lock onto when an instance is created. 

9. What is the `<slot>` element and what is it used for?

  > slots are a way to have a component with injectable data inside of it. Inside of the parent that calls the <component /> can write different html inside of it. 'Hallo' is the customizable html that will still render into the component.

  <component> 
    Hallo
  <component/>
