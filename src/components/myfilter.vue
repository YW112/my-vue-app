<script setup>
let countCat = 3;
</script>

<template>
    <div class="filter-options">
        <ul class="catgr-names">
            <select>
                <option value="">Название категории <p class="three-cats"> {{countCat}} </p></option>
                <option value="">Название категории <p class="three-cats"> {{countCat}} </p></option>
                <option value="">Название категории <p class="three-cats"> {{countCat}} </p></option>
                <option value="">Название категории <p class="three-cats"> {{countCat}} </p></option>
            </select>
        </ul>
        <p class="cost">Цена</p>
        <div class="from-box-to">
            <div class="from-to"> <p class="word-from">от</p>5 500 ₽</div>
            <svg class="dash" width="10" height="2" viewBox="0 0 10 2" fill="none" xmlns="http://www.w3.org/2000/svg">
                <rect y="0.5" width="10" height="1" fill="#D5D5D5"/>
            </svg>
            <div class="from-to"> <p class="word-from">от</p>5 500 ₽</div>
        </div>
        <div>
            <div class="brand-clear">
                <p>Бренд</p>
                <a>Очистить</a>
            </div>
            <input class="mini-search" type="search">
            <form class="over-scroll">
                <input class="check-atr-3 " type="checkbox" name="atr-3-1" value="Атрибут 3"><label for="atr-3-1">Атрибут<p>3</p></label>
                <br>
                <input class="check-atr-3" type="checkbox" name="atr-3-2" value="Атрибут 3"> <label for="atr-3-2">Атрибут<p>3</p></label>
                <br>
                <input class="check-atr-3" type="checkbox" name="atr-3-3" value="Атрибут 3"><label for="atr-3-3">Атрибут<p>3</p></label>
                <br>
                <input class="check-atr-3" type="checkbox" name="atr-3-4" value="Атрибут 3"><label for="atr-3-4">Атрибут<p>3</p></label>
                <br>
                <input class="check-atr-3" type="checkbox" name="atr-3-5" value="Атрибут 3"><label for="atr-3-5">Атрибут<p>3</p></label>
                <br>
                <input class="check-atr-3" type="checkbox" name="atr-3-6" value="Атрибут 3"><label for="atr-3-6">Атрибут<p>3</p></label>
                <br>
                <input class="check-atr-3" type="checkbox" name="atr-3-6" value="Атрибут 3"><label for="atr-3-6">Атрибут<p>3</p></label>
                <br>
                <input class="check-atr-3" type="checkbox" name="atr-3-6" value="Атрибут 3"><label for="atr-3-6">Атрибут<p>3</p></label>
                <br>
                <input class="check-atr-3" type="checkbox" name="atr-3-6" value="Атрибут 3"><label for="atr-3-6">Атрибут<p>3</p></label>
            </form>
            <div class="sizes">Размеры</div>
            <form class="over-scroll">
                <input class="check-atr-3 " type="checkbox" name="atr-3-1" value="Атрибут 3"><label for="atr-3-1">Атрибут<p>3</p></label>
                <br>
                <input class="check-atr-3" type="checkbox" name="atr-3-2" value="Атрибут 3"> <label for="atr-3-2">Атрибут<p>3</p></label>
                <br>
                <input class="check-atr-3" type="checkbox" name="atr-3-3" value="Атрибут 3"><label for="atr-3-3">Атрибут<p>3</p></label>
                <br>
                <input class="check-atr-3" type="checkbox" name="atr-3-4" value="Атрибут 3"><label for="atr-3-4">Атрибут<p>3</p></label>
                <br>
                <input class="check-atr-3" type="checkbox" name="atr-3-5" value="Атрибут 3"><label for="atr-3-5">Атрибут<p>3</p></label>
                <br>
                <input class="check-atr-3" type="checkbox" name="atr-3-6" value="Атрибут 3"><label for="atr-3-6">Атрибут<p>3</p></label>
                <br>
                <input class="check-atr-3" type="checkbox" name="atr-3-6" value="Атрибут 3"><label for="atr-3-6">Атрибут<p>3</p></label>
                <br>
                <input class="check-atr-3" type="checkbox" name="atr-3-6" value="Атрибут 3"><label for="atr-3-6">Атрибут<p>3</p></label>
                <br>
                <input class="check-atr-3" type="checkbox" name="atr-3-6" value="Атрибут 3"><label for="atr-3-6">Атрибут<p>3</p></label>
            </form>
        </div>
    </div>
</template>

<style>
body {
    background-color: rgba(255, 255, 255, 1);
    display: flexbox;
    padding-left: 2.25rem;
    margin: 0;
    flex-wrap: wrap;
}
.filter-options {
    margin-right: 3rem;
    float: left;
    @media screen and (max-width: 360px) {
        display: none;
    }
}
.filter-div {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0px;
    gap: 28px;
    width: 280px;
    height: 760px;
    background: #FFFFFF;
}
.cost {
    display: flex;
    justify-content: center;
    margin: 0 auto;
    width: 36px;
    height: 20px;
    font-family: 'PT Sans';
    font-style: normal;
    font-weight: 700;
    font-size: 16px;
    line-height: 20px;
    color: #333333;
    margin-bottom: 1rem;

}
.catgr-names {
    display: flex;
    flex-direction: column;
    color: black;
    list-style: none;
}
select {
    background-color: white;
    color: rgba(51, 51, 51, 1);
}
.catgr-names > select > option {
    color: rgba(51, 51, 51, 1);
    border-color: aqua;
    justify-content: space-between;
    background-color: white;
    box-sizing: border-box;
}
.catgr-names > select > option:hover {
    background-color: rgb(173, 203, 240);
}
.three-cats {
    color: rgba(170, 170, 170, 1);
}
.from-to {
    background-color: #FFFFFF;
    padding-left: 2rem;
    display: flexbox;
    color: rgba(51, 51, 51, 1);
    box-sizing: border-box;
    display: flex;
    flex-direction: row;
    align-items: center;
    padding: 10px 8px;
    gap: 6px;
    width: 119px;
    height: 36px;
    background: #FFFFFF;
    border: 1px solid #D5D5D5;
    border-radius: 4px;
}
.dash{
    color: #333333;
    margin-left: 0.75rem;
    display: flex;
    padding-right: 5%;
    margin-top: 1.25rem;
}
.from-box-to {
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
}
.word-from {
    color: rgba(170, 170, 170, 1);
}
.brand-clear {
    display: flexbox;
    flex-direction: column;
    justify-content: space-around;
}
.brand-clear > a {
    width: 48px;
    height: 13px;
    display: inline-flex;
    margin-left: 9rem;
    font-family: 'PT Sans';
    font-style: normal;
    font-weight: 400;
    font-size: 12px;
    line-height: 12px;
    text-align: right;
    text-decoration-line: underline;
    color: #AAAAAA;
}
.brand-clear > p {
    display: inline-flex;
    width: 44px;
    height: 20px;
    font-family: 'PT Sans';
    font-style: normal;
    font-weight: 700;
    font-size: 16px;
    line-height: 20px;
    color: #333333;
}
.mini-search {
box-sizing: border-box;
display: flex;
flex-direction: row;
align-items: flex-start;
padding: 10px 12px;
gap: 8px;
width: 280px;
height: 36px;
background-color: #FFFFFF;
border: 1px solid #D5D5D5;
border-radius: 4px;
}
.check-atr-3 {
    display: inline-block;
    color: #AAAAAA;
    align-content: center;
    justify-content: center;
}
.check-atr-3:checked {
    color: rgba(115, 151, 245, 1);
}
label {
    width: 49px;
    height: 16px;
    font-family: 'PT Sans';
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 16px;
    color: #333333;
    display: inline;
    flex-direction: row;
    padding: auto;
    align-content: center;
    justify-content: center;
    flex-wrap: nowrap;
}
label > p {
    width: 7px;
    height: 14px;
    font-family: 'PT Sans';
    font-style: normal;
    font-weight: 400;
    font-size: 12px;
    line-height: 14px;
    text-align: right;
    color: #AAAAAA;
    display: inline;
    padding-left: 10px;
    align-content: center;
    justify-content: center;
}
.over-scroll {
    overflow-y: scroll;
    scrollbar-color: #CBCBCB;
    border-radius: 10px;
    display: flexbox;
    flex-direction: column;
    align-content: center;
    justify-content: center;
}
.over-scroll::-webkit-scrollbar {
    position: absolute;
    width: 3px;
    height: 121px;
    right: 0px;
    top: 88px;
    background: #CBCBCB;
    border-radius: 10px;
}
.sizes {
    margin: 0 auto;
    width: 52px;
    height: 20px;
    font-family: 'PT Sans';
    font-style: normal;
    font-weight: 700;
    font-size: 16px;
    line-height: 20px;
    color: #333333;
    margin-top: 5rem;
}
</style>