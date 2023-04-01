# littlelemon

To the specific api url:
  path('admin/', admin.site.urls),
  path('',views.index),
  path('api/booking/', include(router.urls)),
  path('api/menu-items/', include('reastaurant.urls')),
  path('auth/', include('djoser.urls')),
  path('auth/', include('djoser.urls.authtoken')),
  path('api-token-auth/', obtain_auth_token),
user need to regist a account and being assigned a token which can be used for api request
