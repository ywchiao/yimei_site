+++
layout = 'list'
title = '2021 News'
type = 'news'

[params]
  imageRef = 'news/2021/images'

[[cascade]]
  [cascade._target]
    path = '/news/2021/**'

  [cascade.params]
    imageRef = 'news/2021/images'
+++

一些內容
