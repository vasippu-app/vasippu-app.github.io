---
layout: post
title: "Getting Started with Vasippu Theme"
date: 2026-08-28 09:00:00 +0000
categories: [Guide, Jekyll]
tags: [tutorial, vasippu, design]
---

Discover how to write, customize, and publish your content effortlessly with **Vasippu**, a lightweight and responsive Jekyll theme.

<!--more-->

## Introduction

Vasippu is designed to prioritize content readability and seamless user interaction. Whether you are sharing technical tutorials, personal thoughts, or software engineering architecture patterns, Vasippu provides a disturbance-free presentation.

> *"Simplicity is about subtracting the obvious and adding the meaningful."* — John Maeda

## Key Highlights

1. **Light & Dark Mode**: Instantly switch visual modes with the sidebar theme button.
2. **Built-in Reading Time**: Dynamic estimation of reading time for every article.
3. **Syntax Highlighting**: Built-in support for Rouge code syntax highlighting across multiple programming languages.

### Code Example: Kotlin Multiplatform

Here is how cleanly code snippets render with single-click copy buttons:

```kotlin
data class Article(
    val id: String,
    val title: String,
    val readTimeMinutes: Int
)

fun printArticleDetails(article: Article) {
    println("Reading '${article.title}' (${article.readTimeMinutes} min read)")
}
```

```swift
struct ArticleView: View {
    let title: String
    
    var body: some View {
        Text(title)
            .font(.headline)
            .padding()
    }
}
```

## Summary

To publish a new post, simply drop a `.md` file into your `_posts` folder following the `YYYY-MM-DD-title.md` naming convention. Happy writing!
