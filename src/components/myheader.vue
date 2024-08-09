<script setup>

</script>

<template>
    <div class="header-prod flex justify-between border-b border-slate-300 px-8">
        <div class="logo-company">
            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M5 21C4.45 21 3.979 20.8043 3.587 20.413C3.19567 20.021 3 19.55 3 19V5C3 4.45 3.19567 3.979 3.587 3.587C3.979 3.19567 4.45 3 5 3H19C19.55 3 20.021 3.19567 20.413 3.587C20.8043 3.979 21 4.45 21 5V19C21 19.55 20.8043 20.021 20.413 20.413C20.021 20.8043 19.55 21 19 21H5ZM6 17H18L14.25 12L11.25 16L9 13L6 17Z" fill="#73AFF4"/>
            </svg>
        <p>Лого</p>
        </div>
        <button class="btn-catalogue">Каталог</button>
        <div class="search__form">
            <form action="" method="GET" class="w-5">
                <input type="search" class="search-prods flex items-center gap-10" placeholder="Поиск по 100 000 товаров" name="name" required-placeholder="">
            </form>
            <svg width="24" height="24" class="icon-1" focusable="false" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M15.5 14H14.71L14.43 13.73C15.41 12.59 16 11.11 16 9.5C16 5.91 13.09 3 9.5 3C5.91 3 3 5.91 3 9.5C3 13.09 5.91 16 9.5 16C11.11 16 12.59 15.41 13.73 14.43L14 14.71V15.5L19 20.49L20.49 19L15.5 14ZM9.5 14C7.01 14 5 11.99 5 9.5C5 7.01 7.01 5 9.5 5C11.99 5 14 7.01 14 9.5C14 11.99 11.99 14 9.5 14Z" fill="#5A5A5A"/>
            </svg>
        </div>
            <a href="_blank" class="info-company ml-10 cursor-pointer">Информация о компании</a>
            <a href="_blank" class="contacts flex ml-10 items-center cursor-pointer">Контакты</a>
            <a href="_blank" class="useful-links ml-10 flex items-center cursor-pointer">Полезные ссылки</a>
    </div>
</template>

<style>
body {
    background-color: rgba(255, 255, 255, 1);
    display: flexbox;
    padding-left: 2.25rem;
    margin: 0;
}
.header-prod {
    box-sizing: border-box;
    display: flex;
    flex-wrap: nowrap;
    flex-direction: row;
    padding: 0.8rem 0;
    justify-content: space-between;
    gap: 0.2rem;
    background: #FFFFFF;
    align-items: center;
    width: 70rem;
}
.logo-company{
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 0.5rem;
    width: Hug (49.063rem);
    height: Fixed (3rem);
    margin-right: 1rem;
}
.logo-company > p {
    display: flex;
    color: rgba(0, 0, 0, 1);
}
.search__form {
    position: relative;
    width: 100%;
    display: flex;
    justify-content: space-between;
    width: 19.939rem;
}
.icon-1 {
    position: absolute;
    display: flexbox;
    padding-left: 1rem;
    align-self: center;
}
.btn-catalogue {
    box-sizing: border-box;
    display: flex;
    flex-direction: row;
    align-items: center;
    padding: 0.5rem 1.5rem;
    gap: 0.6rem;
    width: 6.5rem;
    height: Fixed (3rem);
    border-color: #73AFF4;
    border-radius: 8px;
    color: rgba(0, 0, 0, 1);
    background-color: rgba(255, 255, 255, 1);
}
.search-prods {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    padding: 0.2rem 1rem;
    gap: 0.5rem;
    width: 30.438rem;
    height: 2rem;
    background: #FFFFFF;
    border: 0.063rem solid #73AFF4;
    border-radius: 0.625rem;
}
.search-prods::placeholder {
    display: flex;
    flex-direction: row;
    align-items: center;
    padding-left: 2rem;
    gap: 0.5rem;
}
.info-company {
    margin-left: 15rem;
    display: flex;
    flex-direction: row;
    padding: 0px;
    color: #393939;
    flex-wrap: nowrap;
    text-wrap: nowrap;
    font-size: 1rem;
    font-weight: 400;
    line-height: 17px;
}
.contacts {
    margin-left: 2rem;
    display: flex;
    flex-direction: row;
    padding: 0px;
    color: #393939;
    text-wrap: nowrap;
    flex-wrap: nowrap;
    font-size: 1rem;
    font-weight: 400;
    line-height: 17px;
}
.useful-links {
    margin-left: 2rem;
    display: flex;
    flex-direction: row;
    padding: 0px;
    color: #393939;
    text-wrap:nowrap;
    flex-wrap: nowrap;
    font-size: 1rem;
    font-weight: 400;
    line-height: 17px;
}
</style>
