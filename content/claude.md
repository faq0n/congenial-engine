---
title: Chef Claude
---

While going through Scrimba's course "Learn React", I've really liked their capstone project of building an recipe manager app that is backed by an AI chef. Chef Claude asks the user to provide the ingredients you have at hand to suggest you a recipe that allows you to cook a delicious dish from your leftovers. 

This is quite some fun way to start out learning React and I have finally understood some of React's specific changes that differ from HTML and Vanilla Javascript. As user, you are confronted with a lot of input fields in nowadays webapps. Where you would use a checkbox in pure HTML and Javascript, React makes use of some defaults for checkboxes in a different way. To ensure your checkboxes are working correctly, you need to tell your onClick handlers that it is a controlled component. 

```
<Checkbox name="gluten-free" defaultValue={false}/> 
```
