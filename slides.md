---
theme: seriph
background: https://source.unsplash.com/collection/94734566/1920x1080
class: text-center
highlighter: shiki
lineNumbers: false
drawings:
  persist: false
transition: slide-left
title: 開発MTG WS2 プロダクト開発
mdc: true
---

# 開発MTG WS2 プロダクト開発

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub" title="Open in GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

# Table of contents

<ol>
    <li><a href="/3">課題設定</a></li>
    <li><a href="/4">施策考案</a></li>
    <li><a href="/5">施策で活用できるフィードバックの種類</a></li>
    <li><a href="/7">実行スケジュール</a></li>
</ol>

---

# 課題

フィードバックしにくい環境と原因

<div class="mt-10 text-2xl">
  <ol>
    <li>タスク実行者が受け身</li>
    <li>スキル関係がコミュニケーションに影響する</li>
    <li>上司、FB対象の選択の状況がわからず遠慮する</li>
  </ol>
</div>

---

# 施策

フィードバックしにくい課題を打破するためには

<div class="mt-10 text-2xl">
  <ol>
    <li>タスク公開してメンバー全体で理解する</li>
    <li>PJ理解の勉強会</li>
    <li>タスクが振られた時にフィードバック</li>
    <li>理解度スタンプ</li>
    <li>第三者サブレビュー</li>
    <li>フィードバックチャンネルを用意</li>
  </ol>
</div>

---

# 施策で活用できるフィードバックの種類

第三者の介入ありのフィードバック

<div class="mt-10 text-2xl">
  <ol>
    <li>タスク公開してメンバー全体で理解する</li>
    <li>第三者サブレビュー</li>
    <li>タスクが振られた時にフィードバック</li>
    <li class="opacity-30">理解度スタンプ</li>
    <li class="opacity-30">フィードバックチャンネルを用意</li>
  </ol>
</div>

---

# 施策で活用できるフィードバックの種類

マンツーマンのフィードバック

<div class="mt-10 text-2xl">
  <ol>
    <li class="opacity-30">タスク公開してメンバー全体で理解する</li>
    <li class="opacity-30">第三者サブレビュー</li>
    <li class="opacity-30">タスクが振られた時にフィードバック</li>
    <li>理解度スタンプ</li>
    <li>フィードバックチャンネルを用意</li>
  </ol>
</div>

---

# 施策実行スケジュール

| 施策名             | FBの定義   | 試験運用期間 | 施策開始日 |
| ------------------ | ---------- | ------------ | ---------- |
| 理解度スタンプ     | 具体的な例 | 11/1~11/30   | 12/1~      |
| 第三者レビュー     | リスニング | 11/1~11/30   | 12/1~      |
| GitHub Discussions | 具体的な例 | 未定         | 未定       |

---

<div class="w-full h-full flex place-content-center items-center text-8xl">Fin</div>
