---
layout: post
title: "Graph"
date: 2020-05-24 00:00
categories: post
tags: [algorithm, graph]
comments: true
---

그래프는 트리와 비슷하게 노드와 엣지로 구성되어 있습니다. 그래프에서는 노드를 버텍스, 엣지를 아크라고 부릅니다. 사실 그냥 노드랑 엣지로 불러도 상관 없지만, 있어보이려면 버텍스와 아크로 부르도록 합시다.

그래프는 버텍스 간에 여러 개의 아크가 존재할 수 있습니다. 다른 버텍스에서부터 오는 아크의 개수를 In-degree, 다른 버텍스로 가는 아크의 개수를 Out-degree라고 부릅니다. 또한 방향성을 띄고 있는지에 따라 방향 그래프와 무방향 그래프로 나뉩니다.