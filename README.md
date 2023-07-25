# TonySchneider's Portfolio Website

This repository contains the source code for TonySchneider's portfolio website. It's a Django-based project that showcases Tony's work and skills.

## Getting Started

To get started with this project, follow these steps:

1. Install the required Python packages using pip:

```bash
pip install -r requirements.txt
```

2. Run the Django server on port 8000:

```bash
python manage.py runserver
```

You can then access the website at `http://127.0.0.1:8000/`.

3. Create a superuser for Django's admin interface:

```bash
python manage.py createsuperuser
```

4. Create a `confidential.py` file in the same directory as your `settings.py` file. This file should contain the following variables:

```python
SECRET_KEY = 'your-secret-key'
ALLOWED_HOSTS = ['your-allowed-hosts']
EMAIL_HOST_USER = 'your-email-host-user'
EMAIL_HOST_PASSWORD = 'your-email-host-password'
```

Replace `'your-secret-key'`, `'your-allowed-hosts'`, `'your-email-host-user'`, and `'your-email-host-password'` with your actual secret key, allowed hosts, email host user, and email host password, respectively.

## Repository Structure

The repository is structured as follows:

- `base`: Contains the base Django configuration.
- `static`: Contains static files like CSS, JavaScript, and images.
- `staticfiles`: Contains static files collected from all applications.
- `templates`: Contains Django HTML templates.
- `tonyschneider`: Contains the main Django project settings.

Other important files include:

- `.gitignore`: Specifies which files and directories Git should ignore.
- `LICENSE`: The license for this project, which is the MIT license.
- `Procfile`: Used for deploying the application to platforms like Heroku.
- `README.md`: This file, which provides information about the project.
- `manage.py`: A command-line utility for administrative tasks.
- `requirements.txt`: Lists the Python dependencies for this project.
- `runtime.txt`: Specifies the Python version for platforms like Heroku.

## Languages Used

This project is written in:

- JavaScript (60.6%)
- CSS (29.1%)
- HTML (5.8%)
- Python (4.5%)

## Contributing

Contributions are welcome! Please feel free to submit a pull request.

## License

This project is licensed under the terms of the MIT license. See the `LICENSE` file for details.

## Contact

If you have any questions or feedback, please feel free to contact TonySchneider.

## Acknowledgements

Thanks to all the contributors who have helped to improve this project.
