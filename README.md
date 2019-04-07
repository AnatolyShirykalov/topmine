## Форк с поддержкой utf-8 (русских стоп-слов нет)
Зависимостей нет. Работает с python2
### Оригинальное readme
This is an implementation of the algorithm detailed in:
	El-Kishky, Ahmed, et al. "Scalable topical phrase mining from text corpora." Proceedings of the VLDB Endowment 8.3 (2014): 305-316.APA	

In order to run the code, simply follow these steps:
- Put the file on which you want to run topmine in the folder named “input”
- Open topmine.py and change the variable named “file_name” to point at the correct file in the “input” folder.
- Change the “num_topic” variable to the desired value (default value is 4).
- Other configuration changes can be made by changing the variable values in files “run_phrase_mining.py” and “run_phrase_lda.py”.
- Run the command “python topmine.py”
- The results should be available after the execution in the “output” folder.

### Запуск в две команды
```
python2 topmine_src/run_phrase_mining.py input/cognitive.txt
python2 topmine_src/run_phrase_lda.py 2 
```
Здесь `input/cognitive.txt` пример пути к файлу с тестом. Выходные данные в stdout
