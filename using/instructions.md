# Instructions

You can clone this repository

[https://github.com/canada-ca/aia-eia.git](https://github.com/canada-ca/aia-eia.git)

Add the folder to your VS Code workspace

------

In the `ogc_aia` folder, rename the file:

`sample_settings.py`

to

`settings.py`

------

Confirm whether you have Anaconda properly installed:

```bash
conda info
```

If not, verify if you have Python installed:

```bash
python --version
```

Verify that Pip is installed:

```bash
pip --version
```

Install virtualenv

```bash
pip install virtualenv
```

Create your virtual environment:

```bash
conda create --name myenv
```

Activate your environment:

```bash
conda activate myenv
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Test the surver:

```bash
python manage.py runserver
```

Shut down the surver with `Ctrl+C`

Migrate the database

```bash
python manage.py migrate
```

Create a superuser account

```bash
python manage.py createsuperuser
```

Run the surver:

```bash
python manage.py runserver
```

Access the Home page here: `http://127.0.0.1:8000/`

