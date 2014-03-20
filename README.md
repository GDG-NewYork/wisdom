## GDG Wisdom Sandbox
This is an experimental 'sandbox' repo for trying out different ways to present GDG-Wisdom Content.


## Current Version
This first version will use the Sphinx Document Generator to create a themed, searchable, indexed and 
born-printable version of the wisdom content current residing at:
https://sites.google.com/site/gdgwisdom

The Sphinx toolkit leverages python+make to generate and build the content, but the content itself 
is written in a simple markup format (called reStructured Text or rst). 

### Setup
The setup process followed in documented in this article
    http://datadesk.latimes.com/posts/2012/01/sphinx-on-github/
    
To contribute to this repository verify that your dev m/c has python installed (generally available 
on all *nix systems) and install "sphinx" package as described above. Checkout the gh-pages branch.

### Build
After that, to generate new versions, simply:

    1. update the .rst files in the /source directory of the repository
    2. run 'make html' in the root directory to generate the new HTML versions

The html content is then automatically hosted on the gh-pages endpoint at:
http://gdg-newyork.github.io/wisdom

### References
This approach was inspired by the successful usage in http://readthedocs.org, which is used 
by numerous open-source projects to create searchable and well-organized docs for end users.

For an example of how to structure the content and create new themes/features, look at the 
following sites (related to the setup link referenced above)

    1. https://github.com/datadesk/python-documentcloud/blob/master/docs/index.rst (Repo)
    2. [LA Times DocumentCloud Website] (http://python-documentcloud.readthedocs.org/en/latest/)
