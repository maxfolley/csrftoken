csrftoken
=========

jQuery plugin for easy setup of ajax requests in Django 

Usage
-----
Just call the csrftoken on DOM ready:

    $.csrftoken();

Make sure you have the token set in your django template. You can use the following template tag: 

    {% csrf_token %}
