<template>
  <h3 v-for="blog in blogs" :key="blog">
    <slot :blogTitle="blogs.blogTitle" :blogText="blogs.BlogText"></slot>
  </h3>
</template>

<script>
// isim listesinin gosterilmesinden sorumlu
export default {
  name: "NameList",
  data() {
    return {
      blogs: [
        {
          blogTitle:
            "Ex odio ea tempore porro facilis soluta exercitationem et.",
          blogText:
            "Sed nulla rem est. Enim suscipit voluptatibus. Vel et explicabo voluptatum illo blanditiis est delectus.",
          blogLink: "http://twin-sweatshop.name",
          blogAuthor: "Emmitt",
          blogImage: "https://picsum.photos/500",
        },
        {
          blogTitle:
            "Ex odio ea tempore porro facilis soluta exercitationem et.",
          blogText:
            "Sed nulla rem est. Enim suscipit voluptatibus. Vel et explicabo voluptatum illo blanditiis est delectus.",
          blogLink: "http://twin-sweatshop.name",
          blogAuthor: "Emmitt",
          blogImage: "https://picsum.photos/500",
        },
        {
          blogTitle:
            "Ex odio ea tempore porro facilis soluta exercitationem et.",
          blogText:
            "Sed nulla rem est. Enim suscipit voluptatibus. Vel et explicabo voluptatum illo blanditiis est delectus.",
          blogLink: "http://twin-sweatshop.name",
          blogAuthor: "Emmitt",
          blogImage: "https://picsum.photos/500",
        },
        {
          blogTitle:
            "Ex odio ea tempore porro facilis soluta exercitationem et.",
          blogText:
            "Sed nulla rem est. Enim suscipit voluptatibus. Vel et explicabo voluptatum illo blanditiis est delectus.",
          blogLink: "http://twin-sweatshop.name",
          blogAuthor: "Emmitt",
          blogImage: "https://picsum.photos/500",
        },
      ],
    };
  },
};
</script>

<style scoped></style>
