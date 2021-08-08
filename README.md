# todoapp

Just be sure to install all depdendecies first<br>
https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiW1qSi_KDyAhVIZd4KHavXAI0QFnoECAkQAw&url=https%3A%2F%2Fnodejs.org%2F&usg=AOvVaw1tY2p-vJFWJmxWlq4sTxCn
<br>

# Using this project
Onced you've cloned / download this sample project please make sure to run<br>
<code>npm i</code><br>
To install dependecies

# Creating ionic project
Open terminal from any desired location then use this command to create a project<br>
<code>ionic start &lt;project name&gt;</code>

# Run project
Open terminal from your project directory and run this command

<div>
  <b>For browser: </b><br>
  <code>ionic serve</code>
</div>

<div>
  <b>For Android (Requires android studio): </b><br>
  <code>ionic run android</code>
</div>

<div>
  <b>For ios (will work on mac pc): </b><br>
  <code>ionic run ios</code>
</div>

# Create apk
<code>ionic build android</code>

# Creating page
<code>ionic g page &lt;page name&gt;</code>

# Navigating pages
Open a &lt;page-name&gt;.page.ts where you will navigate to another page then add instance of NavController to the constructor
```typescript
    constructor(
      public router:NavController
    ) {}
    
    gotoPage() {
      this.router.navigateForward("what-page");
    }
```
