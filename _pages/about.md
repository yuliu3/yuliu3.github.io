---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!--
<div style="text-align: justify;">
    <ul>
        <li>I am currently an Assistant Professor in the Department of Computing at the Hong Kong Polytechnic University (PolyU).</li>
        <li>I received my Ph.D. degree in Computer Engineering from Stony Brook University, where I had the privilege of working under the guidance of Prof. <a href="http://www.ece.sunysb.edu/~yang/">Yuanyuan Yang</a>. Prior to that, I earned a Bachelor's degree in Telecommunications Engineering from Xidian University, Xi'an, China.</li>
        <li>My research interests include edge computing and networks, edge AI, LEO satellite networks, and distributed quantum computing.</li>
    </ul>
</div>


<br />


News
=====
<div style="text-align: justify;">
    <ul>
        <li><strong>[12/2024]</strong> I am actively recruiting highly motivated Ph.D. students. If you are interested in joining my research group, please send your CV and academic transcripts to my email: <a href="mailto:yu-y.liu@polyu.edu.hk">yu-y.liu@polyu.edu.hk</a>.</li>
    </ul>
</div>
-->
<div className="mt-8 space-y-8">
  <div className="flex gap-8 items-start">
    <img
      src="images/yuliu3.jpg"
      alt="Yu Liu"
      className="w-48 h-auto object-cover rounded-lg shadow-md"
    />
    
    <div className="space-y-6 text-gray-600">
      <div>
        <h3 className="font-bold text-gray-800 mb-2">Position</h3>
        <p>Assistant Professor</p>
        <p>Department of Computing</p>
        <p>Hong Kong Polytechnic University</p>
      </div>

      <div>
        <h3 className="font-bold text-gray-800 mb-2">Email</h3>
        <a href="mailto:yu-y.liu@polyu.edu.hk" 
           className="text-blue-600 hover:text-blue-800 flex items-center gap-2">
          <Mail className="w-4 h-4" />
          yu-y.liu@polyu.edu.hk
        </a>
      </div>
    </div>
  </div>

  <section>
    <h2 className="text-2xl font-bold mb-4 text-gray-800">About Me</h2>
    <div className="space-y-4 text-gray-600">
      <p className="text-justify leading-relaxed">
        I am currently an Assistant Professor in the Department of Computing 
        at the Hong Kong Polytechnic University (PolyU).
      </p>
      <p className="text-justify leading-relaxed">
        I received my Ph.D. degree in Computer Engineering from Stony Brook University, 
        where I had the privilege of working under the guidance of Prof. Yuanyuan Yang. 
        Prior to that, I earned a Bachelor's degree in Telecommunications Engineering 
        from Xidian University, Xi'an, China.
      </p>
      <div className="text-justify leading-relaxed">
        <p className="mb-2">My research interests include:</p>
        <ul className="list-disc pl-8 space-y-1">
          <li>Edge computing and networks</li>
          <li>Edge AI</li>
          <li>LEO satellite networks</li>
          <li>Distributed quantum computing</li>
        </ul>
      </div>
    </div>
  </section>

  <section>
    <h2 className="text-2xl font-bold mb-4 text-gray-800">Education</h2>
    <div className="space-y-6 text-gray-600">
      <div className="space-y-2">
        <p className="font-medium">Ph.D. in Computer Engineering</p>
        <p>Stony Brook University</p>
        <p className="italic">Advisor: Prof. Yuanyuan Yang</p>
      </div>
      
      <div className="space-y-2">
        <p className="font-medium">B.E. in Telecommunications Engineering</p>
        <p>Xidian University</p>
        <p>Xi'an, China</p>
      </div>
    </div>
  </section>

  <section>
    <h2 className="text-2xl font-bold mb-4 text-gray-800">News</h2>
    <div className="space-y-4">
      <div className="flex gap-4 items-start">
        <span className="text-gray-500 font-medium whitespace-nowrap mt-0.5">[12/2024]</span>
        <p className="text-justify leading-relaxed text-gray-600">
          I am actively recruiting highly motivated Ph.D. students. If you are interested 
          in joining my research group, please send your CV and academic transcripts to 
          my email: <a href="mailto:yu-y.liu@polyu.edu.hk" className="text-blue-600 hover:text-blue-800">
          yu-y.liu@polyu.edu.hk</a>.
        </p>
      </div>
    </div>
  </section>
</div>
