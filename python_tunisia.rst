:title: Python Programming Launguage
:author: Ghassen Telmoudi
:description: Python Tunisia presents python programming language on the SFD 2014.
:keywords: presentation, restructuredtext, impress.js, tutorial
:css: tutorial.css



    .. title:: Python Tunisia


----

# whoami
========
.. image:: images/Ghassen-Telmoudi.jpeg
.. code:: python
    
    # I am a
    print(
        "Pythonista since 2009",
        "Founded Python Tunisia Community"
        "Open Source fanatic",
        "Developing a cloud infrasturcture managment solution",
        "Blessed to code python on my day job"
    )
    
    # yeah I have 6000+ unread emails, one day I will trash them all.
    email = "ghassen.telmoudi@gmail.com"
    # I love that place.
    github = "https://github.com/pyghassen"

----

Python, do you know it?
=======================



.. image:: images/what-is-python.jpg

.. code:: python

    print("Classic Jacky what!")


----

.. image:: images/python-logo-master-v3-TM.png

.. code:: python

    python_info = [
        "High level",
        "General purpose",
        "Open Source",
        "Multi-paradigm (Oject Oriented and Functional)",
        "Interpreted and Interactive",
        "Cross-platform",
    ]

.. _Python: http://www.python.org

----

.. image:: images/Guido-Van-Rossum.jpeg
.. code:: python
    
    python = {
        "who": "Python founder",
        "name": "Guido Van Rossum",
        "when": "1991",
        "where": "The Netherlands",
    }

----

Hello Python Tunisia in C
=========================

.. code:: c
    
    #include<stdio.h>

    int main() 
    {
        printf("Hello Python Tunisia!\n");
        return 0;
    }; 

    // 63 characters and 6 lines! }


----

Hello Python Tunisia in Java
============================

.. code:: java
    
    import java.io.*;
    public class Helloworld
    {
      public static void main(String[] args)
        { 
          System.out.println("Hello Python Tunisia!");
        }
    }

    // comes in at a 115 characters and a verbose 8 lines!

----
 
Hello Python Tunisia in Python
==============================

.. code:: python
    
    print("Hello World")

    # Comes in as little as 20 characters and only 1 line

----

.. image:: images/ancient_aliens_guy.jpg

.. code:: python

    print("The ancient aliens guy said it!")

----

Python philosophy
=================

.. code:: python

    >>> import this

    The Zen of Python, by Tim Peters

    Beautiful is better than ugly.
    Explicit is better than implicit.
    Simple is better than complex.
    Complex is better than complicated.
    Flat is better than nested.
    Sparse is better than dense.
    Readability counts...

----

Python Data types
=================

.. code:: python
    
    _list = ["Python", "Tunisia", "on", "SFD"]
    tuple = (1, 2, 3)

    _set = {"this", "a", "set"}
    dictionary = {
        "date", "2014-10-19",
        "location": "Monastir, Tunisia"
    }
    string = "yeah you guessed it, this a string"
    _int = 23
    _float = 9.99

----

Python functions
=================

.. code:: python

    def hello(name):
        """
        Says Hello.

        @name: string
        
        """
        message = "hello {}".formt(name)
        print(message)


----

Python functions
=================

.. code:: python

    def say_many_hellos(name, times=3):
        """
        Says Hello N times.

        @name: string
        @times: int

        """
        messages = ["hello {}\n".formt(name) for name in range(len(times)]
        # Joins the list of messages and returns them as one String.
        return "".join(messages)

----

Python Class
=================

.. code:: python

    class Developper(object):
        """
        Defines a developer object.
        """
        def __init__(self, name):
            """
            @name: string
            """
            self.name = name

        def say_hello(self):
            """
            Ruturs a friendly message.

            """

            return "Hello my name is {}".format(self.name)

    if __name__ == '__main__':
        developer = Developper("Ghassen Telmoudi")
        developer.say_hello()

----

Python Tunisia
==============
.. image:: images/python_tunisia.png

----

Python and education in Tunisia
================================
.. code:: python

    print("You should learn it in school.")

----


That's all folks!
=================

.. image:: images/ancient_aliens_guy.jpg

.. code:: python

    print("I know you're hungry, but it' time to some Qs")


----


y.
