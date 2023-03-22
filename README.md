# VS Code REST Client extension

VS Code REST Client is an extension that allows you to send HTTP requests and view the response directly in Visual Studio Code. It supports multiple HTTP methods such as GET, POST, PUT, DELETE, etc.

Using this extension, you can easily test your APIs without leaving the editor. You can also save requests as files and share them with your team.

To use the VS Code REST Client, you need to install the extension from the VS Code marketplace. Once installed, you can create a new file with the '.http' extension and start writing your HTTP requests.

Here is an example of a simple GET request using the VS Code REST Client:

```
GET <https://jsonplaceholder.typicode.com/todos/1>

```

To send the request, you can either click on the 'Send Request' button in the editor or use the keyboard shortcut 'Ctrl+Alt+R'.

The response will be displayed in a new tab in the editor, and you can view the response headers, body, and status code.

In addition to sending requests, you can also set headers, query parameters, and request body using the VS Code REST Client.

Overall, the VS Code REST Client is a great tool for developers who work with APIs and want to streamline their workflow. It's easy to use and saves a lot of time.

Para testar, vamos utilizar o endereço: https://jsonplaceholder.typicode.com/todos/1

O código dentro do novo arquivo criado: req-testes.http ficou assim:
```
GET https://jsonplaceholder.typicode.com/todos/1 HTTP/1.1
```

