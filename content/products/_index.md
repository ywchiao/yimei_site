+++
layout = 'product'
title = 'products'
type = 'brands'

[params]

[[cascade]]
  [cascade._target]
    path = '/products/**'

  [cascade.params]
    imageRef = '/images'
+++

一些內容
