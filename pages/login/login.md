---
title: User Login
slug: user-login
navbar_class: navbar-dark bg-inverse

form:
  name: login
  action:
  method: post

  fields:
      - name: username
        id: username
        type: text
        placeholder: Username
        autofocus: true
        classes: form-control form-control-lg

      - name: password
        id: password
        type: password
        placeholder: Password  
        classes: form-control form-control-lg        
---
