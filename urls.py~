from django.conf.urls import patterns, include, url

from django.contrib import admin
from django.contrib.auth.views import password_change
from django.contrib.auth.views import password_change_done

from django.contrib.auth.models import User
from django.contrib.sessions.models import Session
admin.autodiscover()

urlpatterns = patterns('',
    # Examples:
    # url(r'^$', 'dt_project.views.home', name='home'),
    # url(r'^blog/', include('blog.urls')),

    url(r'^admin/', include(admin.site.urls)),
)
