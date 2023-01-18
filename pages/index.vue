<template>
  <div class="bg-slate-900 p-12">
    <prism>
      <pre class="line-numbers language-apex overflow-hidden" data-line="1-7,"><code v-pre>public MarketingContactTarget(Contact contact) {
      this.record = contact;
      Integer len = 10;
      Blob blobKey = crypto.generateAesKey(128);
      String key = EncodingUtil.convertToHex(blobKey);
      fakeId = key.substring(0,len);
        </code></pre>
    </prism>
    <prism>
      <pre><code class="language-diff-javascript line-numbers" data-line="9-13">{{ code }}</code>
      </pre>
    </prism>
  </div>
</template>

<script setup>
const code = `import {x, y} as p from 'point';
const ANSWER = 42;

class Car extends Vehicle {
  constructor(speed, cost) {
    super(speed);

    var c = Symbol('cost');
    this[c] = cost;

    this.intro = \`This is a car runs at
      \${speed}.\`;
  }
}

for (let num of [1, 2, 3]) {
  console.log(num + 0b111110111);
}

function $initHighlight(block, flags) {
  try {
    if (block.className.search(/\bno\-highlight\b/) != -1)
      return processBlock(block.function, true, 0x0F) + ' class=""';
  } catch (e) {
    /* handle exception */
    var e4x =
        <div>Example
            <p>1234</p></div>;
  }
  for (var i = 0 / 2; i < classes.length; i++) {
  // "0 / 2" should not be parsed as regexp
    if (checkCondition(classes[i]) === undefined)
      return /\d+[\s/]/g;
  }
  console.log(Array.every(classes, Boolean));
}

export  $initHighlight;`
</script>
