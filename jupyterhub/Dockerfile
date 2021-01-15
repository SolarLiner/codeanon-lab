FROM jupyterhub/jupyterhub

COPY jupyterhub_config.py .

RUN wget https://raw.githubusercontent.com/jupyterhub/jupyterhub/0.9.3/examples/cull-idle/cull_idle_servers.py

RUN pip install dockerspawner oauthenticator
