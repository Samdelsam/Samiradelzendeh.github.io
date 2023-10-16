<script>
export default {
  name: 'HeaderPor',
}
</script>

<template>
  <header>
    <div class="header__wrap">
      <nav class="header__nav">
        <ul class="header_nav_list">
          <li class="header_nav_item"><a class="header_nav_link">Biography</a></li>
          <li class="header_nav_item"><a class="header_nav_link">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<style scoped>
  header{
    color: var(--secondary-color);
    padding: 1.5rem 0;
    position: absolute;
    top: 0;
    transition: opacity .6s ease,transform .6s ease,background-color .6s ease;
    width: 100%;
    z-index: 100002;
  }

  .header__wrap {
    align-items: baseline;
    display: flex;
    position: relative;
    text-transform: uppercase;
    padding: 0 40px;
  }


  .header__nav{
    margin-left: auto;
  }

  .header_nav_list{
    align-items: center;
    display: flex;
    list-style-type: none;
  }

  .header_nav_item{
    margin-right: 1.2rem;
  }

  .header_nav_link{
    font-size: 1.2rem;
    font-weight: 500;
    letter-spacing: -.03em;
    line-height: 1.2142857143;
    position: relative;
    text-decoration: none;
  }
</style>