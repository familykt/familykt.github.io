---
layout: default
title: Translation Test
permalink: /about/
---

# Translation Test Page

## Auto-translate Section
This section can be translated by translation tools.

## No Translation Section
<div translate="no">
  This content should NOT be translated:
  - BrandName™
  - ProductX®
  - CompanyZ©
</div>

## Mixed Translation Example
Our company <span translate="no">TechCorp International®</span> provides global services.
Visit our website at <span translate="no">www.techcorp-example.com</span>

## Technical Terms
<div translate="no">
  Technical terms that should remain unchanged:
  - API_KEY_SECRET
  - AWS_ACCESS_TOKEN
  - DATABASE_URL
</div>

## Translation Controls Demo
<div class="translation-demo">
  <p>This text can be translated</p>
  <p translate="no">이 한글 텍스트는 번역되지 않아야 합니다</p>
  <p translate="no">この日本語テキストは翻訳されないはずです</p>
  <p translate="no">这段中文文本不应被翻译</p>
</div>

## Usage Notes
- Elements marked with `translate="no"` should remain in their original language
- Default behavior (without translate attribute) allows translation
- This page demonstrates proper usage of the HTML translate attribute
