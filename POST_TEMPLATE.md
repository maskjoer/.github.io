# 文章录入模板

将下面对象复制到 posts.js 的数组最前面，并替换为你的真实内容。

```js
{
  slug: "your-unique-slug",
  title: "你的文章标题",
  date: "2026.03.17",
  category: "前端",
  readingTime: "6 分钟",
  tags: ["博客", "实战", "总结"],
  summary: "这篇文章的一句话摘要。",
  content: [
    "第一段正文。",
    "第二段正文。",
    "第三段正文。"
  ]
}
```

## 推荐 slug 规则

- 仅使用小写英文、数字和短横线
- 示例：how-i-build-my-blog-workflow

## 常用分类建议

- 前端
- 后端
- 工具
- 工作流
- 写作
- 设计
- 成长

## 提交发布

```bash
git add posts.js
git commit -m "feat: add new post"
git push origin main
```
