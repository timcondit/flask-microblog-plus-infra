# README

A microblog built using Miguel Grinberg's [Flask
Mega-Tutorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world)
to learn Flask web development.

## Activate

Follow these steps to get it working:

> cd $REPO
> git checkout develop
> python3 -m venv venv
> source venv/bin/activate
> pip install -r requirements.txt
> cd migrations/
> flask db upgrade head

This is known to work with tag `v0.7`. Later versions should also work.
