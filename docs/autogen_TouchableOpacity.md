---
id: touchableopacity
title: TouchableOpacity
sidebar: api
category: Components
permalink: docs/touchableopacity.html
---
<div><div><p>A wrapper for making views respond properly to touches.
On press down, the opacity of the wrapped view is decreased, dimming it.</p><p>Opacity is controlled by wrapping the children in an Animated.View, which is
added to the view hiearchy.  Be aware that this can affect layout.</p><p>Example:</p><div class="prism language-javascript">renderButton<span class="token punctuation">:</span> <span class="token keyword">function</span><span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  <span class="token keyword">return</span> <span class="token punctuation">(</span>
    <span class="token operator">&lt;</span>TouchableOpacity onPress<span class="token operator">=</span><span class="token punctuation">{</span><span class="token keyword">this</span><span class="token punctuation">.</span>_onPressButton<span class="token punctuation">}</span><span class="token operator">&gt;</span>
      <span class="token operator">&lt;</span>Image
        style<span class="token operator">=</span><span class="token punctuation">{</span>styles<span class="token punctuation">.</span>button<span class="token punctuation">}</span>
        source<span class="token operator">=</span><span class="token punctuation">{</span><span class="token function">require</span><span class="token punctuation">(</span><span class="token string">'./myButton.png'</span><span class="token punctuation">)</span><span class="token punctuation">}</span>
      <span class="token operator">/</span><span class="token operator">&gt;</span>
    <span class="token operator">&lt;</span><span class="token operator">/</span>TouchableOpacity<span class="token operator">&gt;</span>
  <span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span><span class="token punctuation">,</span></div></div><h3><a class="anchor" name="props"></a>Props <a class="hash-link" href="docs/touchableopacity.html#props">#</a></h3><div class="props"><div class="prop"><h4 class="propTitle"><a class="anchor" name="touchablewithoutfeedback"></a><a href="docs/touchablewithoutfeedback.html#props">TouchableWithoutFeedback props...</a> <a class="hash-link" href="docs/touchableopacity.html#touchablewithoutfeedback">#</a></h4></div><div class="prop"><h4 class="propTitle"><a class="anchor" name="activeopacity"></a>activeOpacity?: <span class="propType">number</span> <a class="hash-link" href="docs/touchableopacity.html#activeopacity">#</a></h4><div><p>Determines what the opacity of the wrapped view should be when touch is
active. Defaults to 0.2.</p></div></div><div class="prop"><h4 class="propTitle"><a class="anchor" name="focusedopacity"></a>focusedOpacity?: <span class="propType">number</span> <a class="hash-link" href="docs/touchableopacity.html#focusedopacity">#</a></h4></div><div class="prop"><h4 class="propTitle"><a class="anchor" name="tvparallaxproperties"></a>tvParallaxProperties?: <span class="propType">object</span> <a class="hash-link" href="docs/touchableopacity.html#tvparallaxproperties">#</a></h4><div><p>Apple TV parallax effects</p></div></div></div><span><h3><a class="anchor" name="methods"></a>Methods <a class="hash-link" href="docs/touchableopacity.html#methods">#</a></h3><div class="props"><div class="prop"><h4 class="methodTitle"><a class="anchor" name="setopacityto"></a>setOpacityTo<span class="methodType">(value: number, duration: number)</span> <a class="hash-link" href="docs/touchableopacity.html#setopacityto">#</a></h4><div><p>Animate the touchable to a new opacity.</p></div></div></div></span></div>