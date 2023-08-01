<script setup lang="ts">
import { useData } from "vitepress";

const { isDark } = useData();
</script>

<template>
  <div
    class="mt-8 flex flex-col gap-4"
    :class="isDark ? 'text-coolGray-4' : 'text-coolGray-6'"
  >
    <div class="flex gap-4">
      <span>提供元：Neuromatch</span>
      <span>(翻訳：コミュニティメンバー)</span>
    </div>
    <span
      >このリポジトリの内容は
      <a
        href="http://creativecommons.org/licenses/by/4.0/"
        nofollow
        target="_blank"
        rel="noreferrer noopener"
        >Creative Commons Attribution 4.0 International License</a
      >のもとで提供されています。ソフトウェアに関わる部分は
      <a
        href="https://opensource.org/licenses/BSD-3-Clause"
        nofollow
        target="_blank"
        rel="noreferrer noopener"
        >BSD (3-Clause) License</a
      >のもとで提供されています。</span
    >
  </div>
</template>
