<template>
  <div class="w-100">
    <div class="mobileTitle">
      Создание новой темы
    </div>
    <div class="boxContainer">
      <div class="componentPath">
        <div>Ценообразование в строительстве » Вопросы-ответы » <span class="currentName">Новая тема</span>
        </div>
        <div class="goBack hideOnMobile"><img src="@/assets/icons/triangleLeftIcon.svg" class="m-r-5"> Назад</div>
      </div>
      <AddThemeBtn class="hideOnMobile onlySmallDisplays"/>
    </div>
    <div class="create__new__theme__form">
      <div class="create__new__theme__form__container">
        <div class="container__title">
          <h1 class="container__subtitle hideOnMobile">Создание новой темы</h1>
          <hr>
        </div>
        <div class="container__form">
          <div class="container__form__left">
            <div class="conatiner__form__description">
              <span class="form__subtitle">Название темы<span>*</span>:</span>
              <input class="container__form__inp" placeholder="Придумайте название Вашей темы">
            </div>
            <div class="conatianer__form">
              <div class="conatiner__form__description">
                <span class="form__subtitle">Выберите основной раздел<span>*</span></span>
                <form>
                  <select class="container__form__inp select">
                    <option>Ценообразование в строительстве</option>
                  </select>
                </form>
              </div>
            </div>
          </div>
          <div class="container__form__right">
            <div class="conatiner__form__description">
              <span class="form__subtitle">Описание темы<span>*</span>:</span>
              <input class="container__form__inp" placeholder="Описание под темой">
            </div>
            <div class="conatiner__form__description">
              <span class="form__subtitle">Выберите подкатегорию<span>*</span></span>
              <form >
                <select class="container__form__inp select">
                  <option>Вопросы-ответы</option>
                </select>
              </form>
            </div>
          </div>
        </div>
        <div class="container__footer">
          <div class="footer__icon">
            <img src="@/assets/icons/textFormat/boldIcon.svg">
            <img src="@/assets/icons/textFormat/italicIcon.svg" class="m-l-30">
            <img src="@/assets/icons/textFormat/underLineIcon.svg" class="m-l-30">
            <img src="@/assets/icons/textFormat/cupsLookIcon.svg" class="m-l-30">
            <img src="@/assets/icons/textFormat/firsLetterIcon.svg" class="m-l-30">
            <img src="@/assets/icons/textFormat/alignTextRigthIcon.svg" class="m-l-30">
            <img src="@/assets/icons/textFormat/alignTextCenterIcon.svg" class="m-l-30">
            <img src="@/assets/icons/textFormat/alignTextLeftIcon.svg" class="m-l-30">
            <img src="@/assets/icons/textFormat/alignTextFillIcon.svg" class="m-l-30">
            <img src="@/assets/icons/textFormat/linkIcon.svg" class="m-l-30">
            <img src="@/assets/icons/textFormat/listIcon.svg" class="m-l-30">
            <img src="@/assets/icons/textFormat/imageIcon.svg" class="m-l-30">
            <img src="@/assets/icons/textFormat/emojiIcon.svg" class="m-l-30">
          </div>
          <textarea class="footer__inp" placeholder="Ваш текст">
          </textarea>
          <div class="footer__form">
            <div class="footer__form__file">
              <label class="footer__form__file__add">

                <input type="file">
                <div class="footer__form__file__add__btn">
                  +
                </div>
                <span class="footer__form__file__add__text">Прикрепить файл</span>
              </label>
            </div>
            <button class="footer__btn">Опубликовать тему</button>
          </div>
          <hr>
          <span class="footer__subtitle"><span>*</span> Поля, обязательные для заполнения.</span>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  routerData: {
    sdw: true
  }
}
</script>>
