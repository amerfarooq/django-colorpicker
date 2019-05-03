# forms.py

from .widgets import ColorPickerWidget

class MyForm(forms.ModelForm):
    class Meta:
        model = MyModel
        widgets = {
            'color': ColorPickerWidget(),
        }
