![image](https://user-images.githubusercontent.com/96494361/207118490-2d4a7f26-e0df-4c47-8ac6-2af21998eaf8.png)
<ul>
  <li>1. Name-Surname: Alexander Kholyavski;</li>
  <li>2. Contacts:</li>
    <ul>
      <li>telegram - @Spenkau;</li>
      <li>mail - kholyavskij@mail.ru;</li>
      <li>RC-School discord - @Spenkau</li>
    </ul>
  <li>
    <p>
      3. I learning JS about 8 month, started own career with React-dev course, has making project for this, but by some reasons
  this course was closed and I continued education. One month later I impoved skills in vanil JS and been doing this for three months. Later I and my partner started to make fullstack project React & Django where I was responsible for frontend part. 
  This project we make and today.
  My future plans is to be good in fullstack development :) 
    </p>
  </li>

  <li>
    <p>
      4. Skills: JS (middle lvl); React (low level); HTML & CSS (middle lvl); GIT (know how to work in pair - commit, push, pull, clone)
    </p>
  </li>
  <li>
    <p>5. Multi-level sorting on React:</p>

    ```
      const filterByTitle = () => data.filter(item => {
        return value.current.length===0 ? data : item.title.toLowerCase().includes(value.current.toLowerCase())
      })

      const filterByFiller = (fillerValue) => {
        return fillerValue === 2 ? filterByTitle() : filterByTitle().filter((item) => {
          return item.isMeat === fillerValue
        })
      }

      const sortByField = (field) => {
        return field === 'popularity' ? filterByFiller(fillerValue).sort((a, b) => a[field] < b[field] ? 1 : -1) :
            filterByFiller(fillerValue).sort((a, b) => a[field] < b[field] ? -1 : 1)
      }
    ```
    <p>Others my examples in github, expirience with React in dj-react repository.</p>
  </li> 

  <li>
    <p>
      6. One work expirience is making React app with online-DB mockapi for course of one of the companies in my city.</p>
      link - https://github.com/Spenkau/library;
      And current project that i make in pair on React:
      link - https://github.com/MaksimkaFishbain/dj_react_pizza (only frontend folder)
    </p>
  </li>
  <li>
    <p>7. Education: Hrodno college, specialty technician-programmer, sophomore year of college.</p>
  </li>
  <li>
    <p>8. English level is about A2, achieved by school and college practice.</p>
  </li>
</ul>
