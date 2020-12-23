<template>
  <div class="form configurations">
    <div class="container settings">
      <div class="container-settings">
        <ConfigurationBtns />
        <div class="container-settings-right">
          <button class="back-btn pointer">
            <img
              src="@/assets/icons/triangleLeftIcon.svg"
              class="m-l-30 m-r-5"
            />
            Назад
          </button>
          <button class="save-btn pointer">Сохранить</button>
        </div>
      </div>
      <h1 class="container-title">Форум</h1>
      <div class="settings-table-header">Ценообразование в строительстве</div>
      <table class="forumTableContainer categories m-b-75">
        <tr>
          <td>
            <div class="first-row m-t-20">
              <span class="title">Ценообразование в строительстве</span>
              <img src="@/assets/icons/penIcon.svg" class="m-l-20" />
            </div>
          </td>
          <td><span class="delete pointer m-r-17">Удалить</span></td>
          <td>
            <div class="settings-table-icon"><img src="@/assets/icons/lockIcon.svg" /></div>
          </td>
          <td>
            <div class="settings-table-icon"><img src="@/assets/icons/stickyIcon.svg" /></div>
          </td>
          <td><img src="@/assets/icons/drugIcon.svg" /></td>
        </tr>
        <tr>
          <td>
            <div>
              <div class="first-row">
                <span class="title">Работа ПТО</span>
              </div>
              <div class="lastVisit"></div>
            </div>
          </td>
          <td>
            <span class="delete pointer m-r-17" style="display: none">Удалить</span>
          </td>
          <td>
            <div class="settings-table-icon"><img src="@/assets/icons/lockIcon.svg" /></div>
          </td>
          <td>
            <div class="settings-table-icon"><img src="@/assets/icons/stickyIcon.svg" /></div>
          </td>
          <td>
            <img src="@/assets/icons/drugIcon.svg" style="display: none" />
          </td>
        </tr>
        <tr class="specialRow">
          <td>
            <div>
              <div class="first-row">
                <span class="title">
                  Установка и разборка инвентарных лесов</span
                >
              </div>
            </div>
          </td>
          <td>
            <span class="delete pointer m-r-17" style="display: none">Удалить</span>
          </td>
          <td>
            <div class="settings-table-icon"><img src="@/assets/icons/lockIcon.svg" /></div>
          </td>
          <td>
            <div class="settings-table-icon"><img src="@/assets/icons/stickyIcon.svg" /></div>
          </td>
          <td>
            <img src="@/assets/icons/drugIcon.svg" class="m-r-5" />
          </td>
        </tr>
        <tr>
          <td>
            <div>
              <div class="first-row">
                <span class="title">Поиск расценок в ГЭСН, ФЕР, ТЕР и пр.</span>
              </div>
            </div>
          </td>
          <td>
            <span class="delete pointer m-r-17" style="display: none">Удалить</span>
          </td>
          <td>
            <div class="settings-table-icon"><img src="@/assets/icons/lockIcon.svg" /></div>
          </td>
          <td>
            <div class="settings-table-icon"><img src="@/assets/icons/stickyIcon.svg" /></div>
          </td>
          <td>
            <img src="@/assets/icons/drugIcon.svg" style="display: none" />
          </td>
        </tr>
      </table>
      <button class="container-btn m-b-75">+ Добавить категорию</button>
      <div class="settings-table-header">Поиск расценок в ГЭСН, ФЕР, ТЕР и пр.</div>
      <table class="forumTableContainer categories m-b-75">
        <tr>
          <td>
            <div class="first-row m-t-20">
              <span class="title">Общестроительные работы</span>
              <img src="@/assets/icons/penIcon.svg" class="m-l-20" style="display:none"/>
            </div>
          </td>
          <td><span class="delete pointer m-r-17" style="display:none">Удалить</span></td>
          <td>
            <div class="settings-table-icon"><img src="@/assets/icons/lockIcon.svg" /></div>
          </td>
          <td>
            <div class="settings-table-icon"><img src="@/assets/icons/stickyIcon.svg" /></div>
          </td>
          <td><img src="@/assets/icons/drugIcon.svg" style="display:none"/></td>
        </tr>
        <tr>
          <td>
            <div class="first-row">
                <span class="title">Общестроительные работы</span>
            </div>
          </td>
          <td>
            <span class="delete pointer m-r-17" style="display: none">Удалить</span>
          </td>
          <td>
            <div class="settings-table-icon"><img src="@/assets/icons/lockIcon.svg" /></div>
          </td>
          <td>
            <div class="settings-table-icon"><img src="@/assets/icons/stickyIcon.svg" /></div>
          </td>
          <td>
            <img src="@/assets/icons/drugIcon.svg" style="display:none" />
          </td>
        </tr>
        <tr>
          <td>
            <div class="first-row">
                <span class="title">Общестроительные работы</span>
            </div>
          </td>
          <td>
            <span class="delete pointer m-r-17" style="display: none">Удалить</span>
          </td>
          <td>
            <div class="settings-table-icon"><img src="@/assets/icons/lockIcon.svg" /></div>
          </td>
          <td>
            <div class="settings-table-icon"><img src="@/assets/icons/stickyIcon.svg" /></div>
          </td>
          <td>
            <img src="@/assets/icons/drugIcon.svg" class="m-r-5" style="display:none" />
          </td>
        </tr>
        <tr>
          <td>
            <div class="first-row">
                <span class="title">Общестроительные работы</span>
            </div>
          </td>
          <td>
            <span class="delete pointer m-r-17" style="display: none">Удалить</span>
          </td>
          <td>
            <div class="settings-table-icon"><img src="@/assets/icons/lockIcon.svg" /></div>
          </td>
          <td>
            <div class="settings-table-icon"><img src="@/assets/icons/stickyIcon.svg" /></div>
          </td>
          <td>
            <img src="@/assets/icons/drugIcon.svg" style="display: none" />
          </td>
        </tr>
      </table>
      <button class="container-btn m-b-75">+ Добавить категорию</button>
    </div>
  </div>
</template>