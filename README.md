# GPT-assistant by actoweed
gpt assistant for DKFLIMS


Заходим на сайт : https://login.pinecone.io/ и регистрируемся 

Переходим в свой профиль , создаем и копируем API KEY

Переходим в код и вставляем этот ключ в эту строку: os.environ["PINECONE_API_KEY"] = "INSERT YOUR PINECONE API KEY"

Так же вставляем ключ openAI сюда: client = OpenAI(api_key="YOUR OPENAI API KEY") !!! (Ключ выдан в тг)

Загружаем туда файлы, желательно чтобы в файле было так: ''' текст '''

Нажимем сюда, после нажимаем "Change runtime type" и выбираем T4

![image](https://github.com/user-attachments/assets/20e8ce8f-e6aa-493d-be23-1881d071062b)


![image](https://github.com/user-attachments/assets/5f4021c8-bc11-43dd-9760-371188375ec4)

Жмем save 

Поочередно запускаем эти три строчки

![image](https://github.com/user-attachments/assets/d13d1187-d6d2-4609-8187-837619d89b9d)

выбираем папку в google colab, где будут храниться документы в формате TXT 

Например создаем папку в папке etc под названием TXT FILES

Закидываем туда наши файлы копирум к ним путь

![image](https://github.com/user-attachments/assets/0fafafd2-097b-486e-ad74-fc41cf22bc1b)


Вставляем его сюда: file_paths = ["PATH TO YOUR FILES"]  

Запускаем основной код, и если все сделали так, то должно быть что-то такое, только с полем для ввода запроса:

![image](https://github.com/user-attachments/assets/13c68c7b-105c-4c52-bf07-734de705ea91)

Вводим запрос и получаем ответ

<3

