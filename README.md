All credit to https://www.jqueryscript.net/other/Flat-HTML5-Palette-Color-Picker-For-jQuery-colorPick-js.html

```python

# Forms.py

from .widgets import ColorPickerWidget

class MyForm(forms.ModelForm):
    class Meta:
        model = MyModel
        widgets = {
            'color': ColorPickerWidget(),
        }
```
