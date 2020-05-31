---
marp: true
title: 小试 sonic pi
theme: default
---

# 灵魂拷问: 你喜欢电子音乐吗?

---

## 何不用程序员的方式编写属于自己的电子音乐

## sonic pi 可以达成这一愿望

---

![bg width:720px](assets/logo.png)

---

## 弹奏一个音符

`play 59`

如果有对应的音乐基础, 可以使用传统写法

`play :B3` 以上等价

---

## 和旋

```
play 55
play 65
play 69
```

---

## 旋律

```
play 55
sleep 1
play 65
sleep 1
play 69
sleep 1
```

这么写感觉好啰嗦, 我们可以简化一下

`play_pattern_timed [55, 65, 69], [1, 1, 1]`

---

## 重复

```
2.times do
  play_pattern_timed [55, 65, 69], [1, 1, 1]
end
```

---

## live loop

---

## 合成器

---

## 效果器

---

## 小样

---

## 随机化

---

## 组合在一起