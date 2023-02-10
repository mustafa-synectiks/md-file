```js
const card = document.querySelector(".card");
const cardContent = card.textContent;
const wordCount = cardContent.split(" ").length;

if (wordCount > 30) {
  card.style.overflow = "scroll";
}
```

<style>
    .card {
  width: 300px;
  height: 200px;
  background-color: white;
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  transition: 0.3s;
  border-radius: 5px;
  overflow: hidden;
}

</style>

<div class="card">
  <p>Your card content here</p>
</div>
