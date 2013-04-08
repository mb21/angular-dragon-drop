# angular-dragon-drop
"Drag and drop" directives for AngularJS. Work in progress.

## Install

```shell
bower install angular-dragon-drop
```

## Use
Repeats a template inside the dragon over a list.
```html
<div btf-dragon="item in list">
  {{item.name}}
</div>
<div btf-dragon="item in otherList">
  {{item.name}}
</div>
```
You can drag from one dragon onto another, and the models will be updated accordingly.

## Config
This is not a kitchen sink every-option-you-can-think-of module. This is a starting point. Configure by forking and editing the code according to your needs.

## Example
See `example.html`.

## License
MIT