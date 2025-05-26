# 👋 eunhyeon kang

</br>

<strong>Instagram</strong>
</br>
@kaeuhy
</br>

<strong>My velog</strong>
</br>
https://velog.io/@kaeuhy/posts

</br>

```
import React from 'react';

const kaeuhy = {
  name: "강은현",
  age: 25,
  education: "Hanbat National Univ",
  affiliation: "WisoftLab",
  studying: ["JavaScript", "TypeScript", "React", "Git"]
};

function Introduction() {
  return (
    <div>
      <h2>👋 자기소개</h2>
      <p><strong>이름</strong>: {kaeuhy.name}</p>
      <p><strong>나이</strong>: {kaeuhy.age}세</p>
      <p><strong>학력</strong>: {kaeuhy.education}</p>
      <p><strong>소속</strong>: {kaeuhy.affiliation}</p>
      <p><strong>스터디</strong>:</p>
      <ul>
        {kaeuhy.studying.map((lang, index) => (
          <li key={index}>{lang}</li>
        ))}
      </ul>
    </div>
  );
}

export default Introduction;
```
