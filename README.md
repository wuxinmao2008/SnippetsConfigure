# SnippetsConfigure
Code snippets  configure file for qt creater IDE.  

## How to use?

- Download `snippets\snippets.xml`, put it to  `C:\Users\%userName%\AppData\Roaming\QtProject\qtcreator\snippets\` dir.

  Usually , you wont see the `snippets` dir, because you haven't use it ! 

- open your QtCreator,  input some thing , just like "connect", you will get tooltips such as `connect with lambda` , `connect with slot`:

  ```c++
      connect(sender, &SenderType::signal, [=](){
          sender->doSomeThings();
      });
  ```

   ![input](.\image\input.gif)

Just like how you got main() function.



### How to add my own code snippet?

You can see below.

![how_to_add](.\image\how_to_add.gif)



### My plan

Just finishied few of core library. All the code are from QAssistant's demo code, I think its enough.

I will add others  when I have enouth time to do this.



Have fun coding with Qt Creator!

