# MDF Examples
Example notebooks showing examples of how to use MDF

# Running Notebooks in Binder
This is the easiest way to run the examples and requires no local setup

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/materials-data-facility/mdf_examples/master)

# Local Installation
```
pip install -r requirements.txt
```

# Globus

## Globus Auth
MDF uses Globus Auth for authentication. Globus Auth is a free service that allows you to authenticate with hundreds of academic institutional credentials and common identity providers (e.g., Google). Creating your user is as easy as visiting <a href="https://www.glous.org">Globus</a> and clicking "Log In" in the upper righthand corner. You can then autnehticate with your institutional credentials, or sign up for a free Globus ID.

Alternatively, you can run these notebooks without authentication by instantiating the `Forge` client anonymously. However, your search results will be limited and your 

```python
mdf = Forge(anonymous=True)
```

## Globus Transfer
If you want to use Globus to transfer files you will need to set up and install a Globus Connect Personal endpoint. <a href="https://www.globus.org/globus-connect-personal">Install Globus Connect</a>

You can also use HTTPS methods to transfer files, but it may be significantly less performant in many situations.

# Support
This work was performed under financial assistance award 70NANB14H012 from U.S. Department of Commerce, National Institute of Standards and Technology as part of the Center for Hierarchical Material Design (CHiMaD). This work was performed under the following financial assistance award 70NANB19H005 from U.S. Department of Commerce, National Institute of Standards and Technology as part of the Center for Hierarchical Materials Design (CHiMaD).
