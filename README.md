## Oxygen Script 2.23
Oxygen Script is a simple compiler that you can use to run simple codes in the front-end environment.

With this simple compiler you can create a simple website and with html and css you can turn it into a big website and publish it.

**Code example:**
```<!DOCTYPE html>
<html>
    <head>
        <meta http-equiv="content-type" content="text/html; charset=utf-8" />
        <title>os</title>
        <script src="/storage/emulated/0/oxygen script/compares.js"></script>
    </head>
    <body>
        <oss>
            os: on
        </oss>
        <os>
            run.html("<h1>oxygen script</h2>")
        </os>
    </body>
</html>
```

### Training to use
When you call the compiler, two tags are added to your html, ``oss`` and ``os``.

The ``oss`` tag is for compiler settings, in order to run the ``os`` tag, you must write ``os: on`` inside it.

You can write your code inside ``os`` tag and after executing the code, your codes will be executed and the result will be displayed to you.

### important things
In the ``os`` tag, only the first line is executed by the compiler. Sometimes, due to some problems, the second line may also be executed and cause your code to be messed up, so it is recommended to use only one in each ``os`` tag.  The code should be written in one line, if you want to write another code, open another tag

Another thing that is worth noting is that there is no need for several ``oss`` tags and only one is enough.
