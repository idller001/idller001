<!doctype html>
<html lang="en-US">
<head>
<title>HTML5 Local Storage Project</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
<meta name="rating" content="General">
<meta name="expires" content="never">
<meta name="language" content="English, EN">
<meta name="description" content="Shopping cart project with HTML5 and JavaScript">
<meta name="keywords" content="HTML5,CSS,JavaScript, html5 session storage, html5 local storage">
<meta name="author" content="dcwebmakers.com">
<script src="Storage.js"></script>
<link rel="stylesheet" href="StorageStyle.css">
  
  <form name="ShoppingList">
    <fieldset>
        <legend>Shopping cart</legend>
        <label>Item: <input type="text" name="name"></label>
        <label>Quantity: <input type="text" name="data"></label>

        <input type="button" value="Save"   onclick="SaveItem()">
        <input type="button" value="Update" onclick="ModifyItem()">
        <input type="button" value="Delete" onclick="RemoveItem()">
    </fieldset>
    <div id="items_table">
        <h2>Shopping List</h2>
        <table id="list"></table>
        <label><input type="button" value="Clear" onclick="ClearAll()">
        * Delete all items</label>
    </div>
</form>
  </head>
  </html>
