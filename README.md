# Boxes

Boxes are a good way to place emphasis when conveying information, complete with a heading and a button that leads to another page. The code below will give you 3 boxes in a row, but it can also be modified to have 2 or even 1 box. This can be achieved by removing 1 or 2 `<div>` tags that have the class `SA-box-container` in their class attribute (`class=""`). After that, make sure that all the `<div>`s that have the `SA-box-container` class have the `col-md-` numbers add up to 12. For example, 2 boxes would use `col-md-6` instead of `col-md-4`. There is a light and dark version of the boxes that can be selected by using either `SA-box-dark` or `SA-box-light` in the class attribute for the `<div>` that has the `SA-box` class.

<img width="1434" height="594" alt="image" src="https://github.com/user-attachments/assets/6319b1a5-b363-408d-92cd-a094fbe17a15" />

```
<div class="container">
    <div class="row SA-box-row">
        <div class="col-md-4 SA-box-container">
            <div class="SA-box SA-box-light">
                <h2 class="text-center">BOX HEADING GOES HERE</h2>
                <hr>
                <p class="text-center">BOX CONTENT GOES HERE</p>
                <div class="SA-box-link-container">
                    <a class="btn btn-primary" href="http://YOUR URL ADDRESS GOES HERE">BUTTON TEXT GOES HERE</a>
                </div>
            </div>
        </div>
        <div class="col-md-4 SA-box-container">
            <div class="SA-box SA-box-light">
                <h2 class="text-center">BOX HEADING GOES HERE</h2>
                <hr>
                <p class="text-center">BOX CONTENT GOES HERE</p>
                <div class="SA-box-link-container">
                    <a class="btn btn-primary" href="http://YOUR URL ADDRESS GOES HERE">BUTTON TEXT GOES HERE</a>
                </div>
            </div>
        </div>
        <div class="col-md-4 SA-box-container">
            <div class="SA-box SA-box-light">
                <h2 class="text-center">BOX HEADING GOES HERE</h2>
                <hr>
                <p class="text-center">BOX CONTENT GOES HERE</p>
                <div class="SA-box-link-container">
                    <a class="btn btn-primary" href="http://YOUR URL ADDRESS GOES HERE">BUTTON TEXT GOES HERE</a>
                </div>
            </div>
        </div>
    </div>
</div>
```
