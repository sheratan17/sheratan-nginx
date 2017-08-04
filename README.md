# Sheratan-NGINX

NGINX yang digunakan di [sheratan.web.id](http://sheratan.web.id) dengan compile:

`./configure --with-http_ssl_module --with-http_v2_module --with-http_gzip_static_module --with-http_auth_request_module --with-http_gunzip_module --with-pcre-jit --without-http_uwsgi_module --without-http_scgi_module --prefix=/opt/nginx`

sederhana yak?

Dibangun di Debian 8 x64

Gunakan dengan resiko sendiri!

Catatan: Versi di buat dengan bentuk "Build X.Y.z"

`git commit -m "build 1"`

Gunakan `/opt/sbin/nginx` untuk memulai atau berhenti
