
# Scholar Space

ScholarSpace is an interactive educational blogging platform that empowers students to share their knowledge, engage in discussions, and foster collaborative learning.
## Features

- **Spaces**: Create and explore educational spaces where students can publish their blogs and initiate discussions.
- **Interactive Discussions**: Engage in dynamic discussions with peers through comments and replies on blog posts.
- **User Profiles**: Customize your profile, showcase your expertise, and connect with like-minded learners.


## Demo

Check out our live demo of ScholarSpace [here](https://web-production-a9ad.up.railway.app/).


## Installation

To run ScholarSpace locally, follow these steps:

1. Clone the repository:

```bash
    git clone https://github.com/thisiskhizar/ScholarSpace.git
```

2. Move into the directory where we have the project files:

```bash
    cd ScholarSpace
```

2. Install dependencies::

```bash
    pip install -r requirements.txt
```

3. Comment out the S3 variables in settings.py if you don't have an S3 bucket set up.

4. Apply migrations:

```bash
    python manage.py migrate
```

5. Start the development server::

```bash
    python manage.py runserver
```

6. Access ScholaSpace by visiting http://localhost:8000 in your browser.
