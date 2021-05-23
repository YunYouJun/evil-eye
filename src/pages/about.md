---
title: About
---

<script setup lang="ts">
import { useI18n } from 'vue-i18n'
const { t } = useI18n()
</script>

<div class="text-center">
  <!-- You can use Vue components inside markdown -->
  <carbon-dicom-overlay class="text-4xl -mb-6 m-auto" />
  <h3>{{t('about.title')}}</h3>
</div>

[evil-eye | 邪王真眼](https://github.com/YunYouJun/evil-eye) 试图在云端发现尘世中人们视线的关注点。

说人话：

> 在浏览器端，监测人类视线关注点。
