<style>
    .todo-task {
        width: 100%;
    }
    .button-container {
        display: flex;
        justify-content: flex-end;
    }
</style>
<div class="form-group">
    <textarea class="no-resize todo-task" id="no-resize" placeholder="Just type it"></textarea>
</div>
<div class="form-group button-container">
    <button class="btn-small paper-btn btn-primary">Save</button>
</div>
<div class="todos">
    <div class="todo form-group">
        <label for="paperChecks1" class="paper-check">
        <input type="checkbox" name="paperChecks" id="paperChecks1" value="option 1"> <span>This is my first item in todo. God knows when this will finish!</span>
        </label>
    </div>
    <div class="todo form-group">
        <label for="paperChecks2" class="paper-check">
        <input type="checkbox" name="paperChecks2" id="paperChecks2" value="option 2"> <span>This is my second item in todo. God knows when this will finish!</span>
        </label>
    </div>
</div>