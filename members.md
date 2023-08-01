<script setup lang="ts">
import { VPTeamMembers } from "vitepress/theme";

const members = [
  {
    avatar: "https://www.github.com/FujishigeTemma.png",
    name: "藤重 天真",
    title: "PhD",
    org: "OIST",
    orgLink: "https://www.oist.jp/ja",
    links: [
      { icon: "github", link: "https://github.com/FujishigeTemma" },
      { icon: "twitter", link: "https://twitter.com/temma_f" },
    ],
  },
  {
    avatar: "https://www.github.com/xShoka.png",
    name: "門井 翔佳",
    org: "KABUTO Technologies",
    links: [
      { icon: "github", link: "https://github.com/xShoka" },
      { icon: "twitter", link: "https://twitter.com/ShokaKadoi" },
    ],
  },
];
</script>

# 翻訳・監修

翻訳に協力してくれるひとを募集しています。一回だけの翻訳でも歓迎です。気軽にコメントやissue、PRとか送ってください🥳

<VPTeamMembers size="small" :members="members" />
