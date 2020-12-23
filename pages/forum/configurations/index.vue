<template>
    <div class="form configurations">
        <div class="container">
            <div class="container-settings">
                <ConfigurationBtns />
                <div class="container-settings-right">
                    <button class="back-btn pointer">
                        <img src="@/assets/icons/triangleLeftIcon.svg" class="m-l-30 m-r-5">
                        Назад
                    </button>
                    <button class="save-btn pointer">Сохранить</button>
                </div>
            </div>
            <h1 class="container-title">Настройки</h1>
            <div class="title-describtion top">
                <div class="m-b-30 row">
                    <div class="inp-label">Кол-во ответов на странице:</div>
                    <input class="inp" placeholder="10">
                </div>
                <div class="description-top row">
                    <div class="inp-label">Темы отображаемые на странице:</div>
                    <input class="inp" placeholder="10">
                </div>
            </div>
            <div class="title-describtion">
                <div class="describtion-bottom m-b-30">
                    <input class="describtion-bottom-checkbox" type="checkbox" checked>
                    <div>Разрешить загрузку файлов</div>
                </div>
                <div class="describtion-bottom">
                    <input class="describtion-bottom-checkbox" type="checkbox">
                    <span>Форум виден только зарегистрированным пользователям</span>
                </div>
            </div>   
        </div>
    </div>
</template>