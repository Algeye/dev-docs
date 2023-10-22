# Django Rest Framework Best Practices

<!--
- Giving more than just number in related fields: https://github.com/encode/django-rest-framework/issues/5141, https://stackoverflow.com/questions/50973569/django-rest-framework-relatedfield-cant-return-a-dict-object
- Results in problems on browsable API.
- For ProductDetailAdminSerializer: Why did we not use WritableNested again? When you override create and update to allow adding m2m fields using set, you have to completely define the create and update and can’t use drf-writable-nested.
-->

## Validation

https://stackoverflow.com/questions/28885018/passing-class-name-as-argument-to-function#:~:text=yes%20of%20coarse%20you%20can,functions%20or%20even%20modules%20...&text=def%20foo()%3A%20pass%20here,'main.
