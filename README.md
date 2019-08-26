# Test-com-Kivy
Somente Teste
#Estou Aprendendo
#11Wills11 = Python Kivy - Associando Widgets


from kivy.app import App
from kivy.uix.button import Button
from kivy.uix.boxlayout import BoxLayout
from kivy.uix.label import Label

class TestApp(App):
    def build(self):
        box = BoxLayout(orientation='vertical')#Se deixar os parenteses fazio ele fica na orizontal
        button = Button(text='Botão 1')
        label = Label(text='Texto 1')
        box.add_widget(button)
        box.add_widget(label)
        return box
        
        box2 = BoxLayout()
        button2 = Button(text='Botão 2')
        label2 = Label(text='Texto 2')
        box2.add_widget(button2)
        box2.add_widget(label2)

        box.add_widget(box2)
        return box
   
        
TestApp().run()
