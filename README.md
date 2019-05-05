All credit to https://www.jqueryscript.net/other/Flat-HTML5-Palette-Color-Picker-For-jQuery-colorPick-js.html
Getting the value from the widget: https://stackoverflow.com/questions/19661484/django-how-to-get-the-selected-value-from-a-custom-widget/19665347#19665347

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
