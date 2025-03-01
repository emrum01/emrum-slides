---
marp: true
style: div.mermaid { all: unset; }
---

# サンプルプレゼンテーション

## Mermaid の例

<div class="mermaid">
graph TD
    A[開始] --> B[処理1]
    B --> C[処理2]
    C --> D[終了]
</div>

---

## 2 ページ目

- 箇条書き 1
- 箇条書き 2
- 箇条書き 3

<script type="module">
import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10.0.0/dist/mermaid.esm.min.mjs';
mermaid.initialize({ startOnLoad: true });
window.addEventListener('vscode.markdown.updateContent', function() { mermaid.init() });
</script>
