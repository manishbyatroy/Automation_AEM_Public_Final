Functions achieve what is defined as the name of the function.
```
javascript:(
    function publishToPreviewSelectorBox() {
        let classes = document.getElementsByClassName('js-editor-PageInfo-closePopover js-editor-WorkflowStart-activator coral3-Button coral3-Button--secondary');
        let Rate = classes[0];
        Rate.click();
        let select = document.getElementsByClassName('js-cq-WorkflowStart-select coral-Form-field coral3-Select');
        let selectChild = select[0].childNodes[0];
        let sibling = selectChild.nextElementSibling;
        sibling.click();}
        )
        ();
```
        
```

        javascript:(function publishPage() {         
            let menuButton = document.getElementsByClassName('js-editor-PageInfo-closePopover cq-authoring-actions-quickpublish-activator coral3-Button coral3-Button--secondary');
            let clickFunc = menuButton[0];
            clickFunc.click();     
            }
             )();
```
