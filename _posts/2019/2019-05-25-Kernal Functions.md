---
layout: post
title:  "Kernal Functions"
date:   2019-05-04 1:29:38 -0800
author: conor
image: 
categories: [machine learning, kernal, kernal functions, dimensionality reduction, linear algebra, python, C#, SVM, singular value matrix, eigenmaps, eigenvalues]
featured: false
visible: 1
---

{:toc}

## Intro

So I was reviewing the "Kernal Trick", and came across a giant list of Kernal Functions to play with.

Problem is all of them are implemented in C# and who in their right mind uses C# for Machine Learning.

I'll give the author some slack though the article was written in 2010, but still why not use Theano or Torch.

So I decided to rewrite them all in an equivalent form in Python and do a comparison to see if my bias against C# is justified.

Then I realized I'd have to get a .NET docker container or something just to compile all the source files, what a drag.

I feel dirty

<a href = /assets/images/dirty.png></a>

From the [github](https://github.com/accord-net/framework)

```
# Install Mono
sudo apt-get install mono-complete monodevelop monodevelop-nunit git autoconf make

# Clone the repository
git clone https://github.com/accord-net/framework.git

# Enter the directory
cd framework

# Build the framework solution using Mono
./autogen.sh
make build
make samples
make test
```

## [Accord-Net](https://github.com/accord-net/framework/tree/development/Sources/Accord.Statistics/Kernels) vs Sci-Py



