pulpito
=======
A dashboard for Zbkc test runs and results. You can see ours here: http://pulpito.zbkc.com/

Setup
=====

#. First, you need a running `paddles <https://github.com/zbkc/paddles/>`_ instance
#. Clone the `repository <https://github.com/zbkc/pulpito.git>`_
#. Inside the repository, create a virtualenv: ``virtualenv ./virtualenv``
#. Create a copy of the configuration template: ``cp config.py.in prod.py``
#. Edit prod.py to reflect your paddles configuration
#. Activate the virtualenv: ``source ./virtualenv/bin/activate``
#. Install required python packages: ``pip install -r requirements.txt``
#. To start the server, you may use ``python run.py`` - though we use `supervisord <http://supervisord.org/>`_ to manage it. A sample config file is provided for `supervisord <supervisord_pulpito.conf>`_.
