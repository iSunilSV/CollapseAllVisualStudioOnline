<b>When viewing Sprint Board in Visual Studio Online, we don't have an option of Collapsing all work items or Expanding all work items.
The below code help you achieve that using a short Javascript code!<b>

<h2>Javascript code for Collpasing All</h2>

```javascript
javascript: function f() 
{ 
  for (var i = 0; i <= 50; i++) { 
    (document.querySelectorAll('[title="Collapse this row"]')[i]).click(); 
  } 
}; f();
```

<h2>Create Bookmark for Collpasing All workitems</h2>

1. Open your browser and on the bookmarks bar, click on 'Add Page' (Chrome) or 'New bookmark' (firefox)
2. In 'Name', write 'Collapse All'
3. In 'URL' or 'Location' copy the Javascript code from above section and paste
4. That's it! Now, you have 'Collapse All' feature which you can use to collapse all open workitems in your sprint backlog board!



<h2>Javascript code for Expanding All</h2>

```javascript
javascript: function f() 
{ 
  for (var i = 0; i <= 50; i++) { 
    (document.querySelectorAll('[title="Expand this row"]')[i]).click(); 
  } 
}; f();
```

<h2>Create Bookmark for Collpasing All workitems</h2>

1. Open your browser and on the bookmarks bar, click on 'Add Page' (Chrome) or 'New bookmark' (firefox)
2. In 'Name', write 'Expand All'
3. In 'URL' or 'Location' copy the Javascript code from above section and paste
4. That's it! Now, you have 'Expand All' feature which you can use to expand all open workitems in your sprint backlog board!
