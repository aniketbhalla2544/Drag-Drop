## Drag & Drop Functionality
<br/>

### Creating Object URL
<p>create object URL reference in memory with `URL.createObjectURL(File)` </p>


<br/>  

### Revoke object URL
</p>Revoke object URL reference from memory with `URL.revokeObjectURL(File)`</p>
<br/>  

### Memory management
<p>Browsers will release object URLs automatically when the document is unloaded; however, for optimal performance and memory usage, if there are safe times when you can explicitly unload them, you should do so.</p> 