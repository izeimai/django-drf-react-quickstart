# django-drf-react-quickstart
Tutorial on Django REST framework for practice

Problem:
Super confused with Django and Django REST framework while working on a volunteer project with Code For Philly.
The original UI people left and I thought it would be great to get back to React. Need to figure out how to combine backend to front!

Solution:
Found a really convenient blog that piece meals together the Django, Django REST framework and React front end:
https://www.valentinog.com/blog/drf/

What's different in this repository from the blog?
Django has moved on to version 2.2 at this time (Nov 2019), so I needed to change some of the syntax in the files that were outdated.
Also there were substantial work arounds needed due to not working on a Mac, so the very early stage set up prompts were not the same.
I don't know if I was laughing or crying when the first line in the blog 'python3 -m venv VenvDjango' didn't even work. Yes, you need conda.

Donloaded Anaconda Prompt (Anaconda3) to generate the virtual environment 'VenvDjango'

conda create -n VenvDjango anaconda
conda activate VenvDjango
conda install -c anaconda django


Initial upload stops right before the testing portion because I don't think we use Cypress for the coding project.











