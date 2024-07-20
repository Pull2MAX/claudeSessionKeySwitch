这是一个用户脚本，用于在多个 Claude 平台上自动登录。通过一个固定在界面右上角的按钮，用户可以方便地切换 sessionKey。脚本提供了一个下拉菜单来持久显示并选择当前的 Token，当选择新的 Token 后，页面将自动重定向到对应的登录地址。重定向的是https://demo.fuclaude.com/和https://claude.asia/

功能特色:

动态下拉菜单: 显示并允许用户从预设的 Token 列表中选择。
蓝色切换按钮: 界面上有一个蓝色按钮，用于切换或重新加载 Token。
菜单展开定位: 菜单将直接在 SessionKey 按钮下方展开，提供直观的操作接口。
自动登录: 根据选择的 Token 自动构建登录 URL 并跳转，简化用户操作。
安全性: 脚本使用 localStorage 来存储用户的选择，虽然存储是安全的，但需要注意 localStorage 是明文存储，可能会被有访问权限的脚本读取。


This user script enables automatic login across multiple Claude platforms. It features a button fixed at the top-right corner of the interface, allowing users to easily switch sessionKeys. The script provides a dropdown menu that persistently displays and selects the current Token, automatically redirecting to the corresponding login URL upon selecting a new Token.

Key Features:

Dynamic Dropdown Menu: Displays and allows the user to choose from a pre-set list of Tokens.
Blue Switch Button: Features a blue button on the interface for toggling or reloading Tokens.
Menu Expansion Positioning: The menu expands directly below the SessionKey button, providing an intuitive user interface.
Automatic Login: Automatically constructs and redirects to the login URL based on the selected Token, simplifying user operations.
Security: The script uses localStorage to store user selections, which is secure, but note that localStorage is stored in plain text and could be read by any script with access.
