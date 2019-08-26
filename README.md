# Test-com-Kivy
Somente Teste
#Estou Aprendendo
#11Wills11 = Python Kivy - criando uma interface gráfica



from kivy.app import App
from kivy.uix.button import Button



class TestApp(App):
    def build(self):
        return Button(text='Olá Mundo')




TestApp().run()
