# flask-auth
A small project to understand the basics of flask-auth

Learning the basics of flask-auth. Feel free to use this project as a reference!

from flask import Flask, render_template, request, url_for, redirect, flash, send_from_directory

from werkzeug.security import generate_password_hash, check_password_hash

from flask_sqlalchemy import SQLAlchemy

from flask_login import UserMixin, login_user, LoginManager, login_required, current_user, logout_user

