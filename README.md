
sudo usermod -aG docker username

docker file
Use COPY for simple file copying tasks where you just need to copy files from the host into the image.
Use ADD when you need additional features such as handling compressed files or downloading files from URLs. However, use it with caution as its behavior can sometimes be unexpected.
