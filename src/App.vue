<template>
  <section>
    <h2>My Friends</h2>
    <ul>
      <li></li>
    </ul>
  </section>
</template>

<script>
export default {
  data() {
    return {
      friends: [
        {
          id: "marat",
          name: "Marat Kulbaev",
          phone: "+996333444555",
          email: "marat@xmpl.com",
        },
        {
          id: "meerim",
          name: "Meerim Tokocheva",
          phone: "+996333444666",
          email: "meepum@xmpl.com",
        },
      ],
    }
  },
}
</script>
