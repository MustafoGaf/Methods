# МЕТОДЫ В JAVA  SCRIPT
## ЧТО ТАКОЕ МЕТОД
В JavaScript методы - это функции, которые находятся внутри свойств объекта и позволяют выполнять определенные действия с этим объектом. Методы в JavaScript – это обычные функции

## КАК СОЗДАЕТСЯ    string в JS

Существуеть три  способа создание строка в js
1. Через двойной кавичка   ""
   
2. Через одной кавичке ''
  
3. Через backticks  ``  преимущество в том что мы можем суда написат какойто другой перемение Б или сложить
  
## МЕТОДЫ STRING

В JAVASCRIPT ДЛЯ STRIGN  СУЩЕСТВЦЕТ НЕСКОЛЬКО МЕТОДОВ НО МЫ БУДЕМ РАСКАЗЗАТ  О САМОЕ РАСПРОСТРАНЕНЫХ КАКИЕ 

![Alt-описание изображения](./src/stringMethod.PNG)

> любие  методи работают таким образом  
>имяПеремения.Метод(параметр)
### charAt()
Это метод принимает один параметр и возвращает символ которые стоить под этому индекс

![Alt-описание изображения](./src/charat.PNG)

### concat()

Этот метод  принимает строку и  обЪеденить их в один строку 
Можно в качества параметр  несколько строку

![Alt-описание изображения](./src/concat.PNG)

### replace()

Принимает два параметр изменитяет  первую папающих в строку первые параметрь на второй параметьр
Возвращает новое строку

![Alt-описание изображения](./src/replace.PNG)

### replaceAll()
Принимает два параметр и изменяеть всех попадающих которые равны первые параметр иизменяеть в строку второй параметр
Возвращает новое строку

![Alt-описание изображения](./src/replaceAll.PNG)

### split()
Принимает два параметр первые разделитьел второй длина новое массива 
split() - метод разбивает строку на массив строк используя для этого заданный разделитель

![Alt-описание изображения](./src/split.PNG)


### substring(start, end)
Возвращает часть строки между start и end (не включая) end


![Alt-описание изображения](./src/substring.PNG)


### slice(start, end)

Метод slice() извлекает часть строки и возвращает новую строку без изменения оригинальной строки.

![Alt-описание изображения](/путь/к/изображению)

### toLowelCase()
Этот метод не принимает параметр 

Метод toLowerCase() возвращает значение строки, на которой он был вызван, преобразованное в нижний регистр.

![Alt-описание изображения](/путь/к/изображению)

### toUpperCase()
Этот метод не принимает параметр 

Метод toUpperCase() возвращает значение строки, на которой он был вызван, преобразованное в верхний регистр.

![Alt-описание изображения](/путь/к/изображению)

### trim()
Этот метод не принимает параметр 

Метод trim() удаляет пробельные символы с начала и конца строки. 

![Alt-описание изображения](/путь/к/изображению)

### includes()

Метод includes() проверяет, содержит ли строка заданную  параметру подстроащает, соответственно true или false.

![Alt-описание изображения](/путь/к/изображению)

### toString()
Не принимае параметр

Метод toString() возвращает строку, любой тип даных

![Alt-описание изображения](/путь/к/изображению)

### indexOf()

Метод indexOf() возвращает индекс первого вхождения указанного значения в строковый объект String, на котором он был вызван, начиная с индекса fromIndex. Возвращает -1, если значение не найдено.

![Alt-описание изображения](/путь/к/изображению)

### repeat(n)

Метод repeat() конструирует и возвращает новую строку, содержащую указанное количество соединённых вместе копий строки, на которой он был вызван.

![Alt-описание изображения](/путь/к/изображению)

### at()

Принимаеть индекс и возвращаеть символ которые состоить под даной индекс 
Примущество в том что если мы хотим получить последную символ строку просто указиваем -1

![Alt-описание изображения](/путь/к/изображению)


# Методы  Number
 > для доступ к методы number мы  вызывае  Math.Метод(параметр)
 
 
### Math.round()

Метод Math.round() возвращает число, округлённое к ближайшему целому.
![Alt-описание изображения](/путь/к/изображению)

### Math.ceil()

Метод Math.ceil() - округление вверх. Округляет аргумент до ближайшего большего целого.

![Alt-описание изображения](/путь/к/изображению)

### Math.floor()

Метод Math.floor() - округление вниз. Округляет аргумент до ближайшего меньшего целого.

![Alt-описание изображения](/путь/к/изображению)

### Math.max()
Принимает один или несколько параметр 

Метод Math.max() возвращает большие число 

![Alt-описание изображения](/путь/к/изображению)

### Math.min()
Принимает один или несколько параметр 

Метод Math.min() возвращает наименьшее из нуля или более чисел.

![Alt-описание изображения](/путь/к/изображению)



- Type some Markdown on the left
- See HTML in the right
- ✨Magic ✨

## Features

- Import a HTML file and watch it magically convert to Markdown
- Drag and drop images (requires your Dropbox account be linked)
- Import and save files from GitHub, Dropbox, Google Drive and One Drive
- Drag and drop markdown and HTML files into Dillinger
- Export documents as Markdown, HTML and PDF

Markdown is a lightweight markup language based on the formatting conventions
that people naturally use in email.
As [John Gruber] writes on the [Markdown site][df1]

> The overriding design goal for Markdown's
> formatting syntax is to make it as readable
> as possible. The idea is that a
> Markdown-formatted document should be
> publishable as-is, as plain text, without
> looking like it's been marked up with tags
> or formatting instructions.

This text you see here is *actually- written in Markdown! To get a feel
for Markdown's syntax, type some text into the left window and
watch the results in the right.

## Tech

Dillinger uses a number of open source projects to work properly:

- [AngularJS] - HTML enhanced for web apps!
- [Ace Editor] - awesome web-based text editor
- [markdown-it] - Markdown parser done right. Fast and easy to extend.
- [Twitter Bootstrap] - great UI boilerplate for modern web apps
- [node.js] - evented I/O for the backend
- [Express] - fast node.js network app framework [@tjholowaychuk]
- [Gulp] - the streaming build system
- [Breakdance](https://breakdance.github.io/breakdance/) - HTML
to Markdown converter
- [jQuery] - duh

And of course Dillinger itself is open source with a [public repository][dill]
 on GitHub.

## Installation

Dillinger requires [Node.js](https://nodejs.org/) v10+ to run.

Install the dependencies and devDependencies and start the server.

```sh
cd dillinger
npm i
node app
```

For production environments...

```sh
npm install --production
NODE_ENV=production node app
```

## Plugins

Dillinger is currently extended with the following plugins.
Instructions on how to use them in your own application are linked below.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Development

Want to contribute? Great!

Dillinger uses Gulp + Webpack for fast developing.
Make a change in your file and instantaneously see your updates!

Open your favorite Terminal and run these commands.

First Tab:

```sh
node app
```

Second Tab:

```sh
gulp watch
```

(optional) Third:

```sh
karma test
```

#### Building for source

For production release:

```sh
gulp build --prod
```

Generating pre-built zip archives for distribution:

```sh
gulp build dist --prod
```

## Docker

Dillinger is very easy to install and deploy in a Docker container.

By default, the Docker will expose port 8080, so change this within the
Dockerfile if necessary. When ready, simply use the Dockerfile to
build the image.

```sh
cd dillinger
docker build -t <youruser>/dillinger:${package.json.version} .
```

This will create the dillinger image and pull in the necessary dependencies.
Be sure to swap out `${package.json.version}` with the actual
version of Dillinger.

Once done, run the Docker image and map the port to whatever you wish on
your host. In this example, we simply map port 8000 of the host to
port 8080 of the Docker (or whatever port was exposed in the Dockerfile):

```sh
docker run -d -p 8000:8080 --restart=always --cap-add=SYS_ADMIN --name=dillinger <youruser>/dillinger:${package.json.version}
```

> Note: `--capt-add=SYS-ADMIN` is required for PDF rendering.

Verify the deployment by navigating to your server address in
your preferred browser.

```sh
127.0.0.1:8000
```

## License

MIT

**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
