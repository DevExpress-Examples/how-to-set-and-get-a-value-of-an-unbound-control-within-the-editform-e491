# How to set and get a value of an unbound control within the EditForm


<p>If you use an unbound control within the EditForm template, you may need to set its value when editing starts, and read it back when editing is done. The HtmlEditFormCreated event must be used to initialize template controls. To read new values, use the RowUpdating and RowInserting events, which are called when editing is done.</p>

<br/>


