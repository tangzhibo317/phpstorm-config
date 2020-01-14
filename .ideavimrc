"          _____                      _____            _____                    _____          
"         /\    \                    /\    \          /\    \                  /\    \         
"        /::\    \                  /::\____\        /::\____\                /::\    \        
"        \:::\    \                /:::|    |       /:::|    |               /::::\    \       
"         \:::\    \              /::::|    |      /::::|    |              /::::::\    \      
"          \:::\    \            /:::::|    |     /:::::|    |             /:::/\:::\    \     
"           \:::\    \          /:::|::|    |    /:::|::|    |            /:::/  \:::\    \    
"           /::::\    \        /:::/|::|    |   /:::/|::|    |           /:::/   /\:::\    \   
"          /::::::\    \      /:::/ |::|    |  /:::/ |::|    | _____    /:::/   /__\:::\    \  
"         /:::/\:::\    \    /::::\ |::|    | /:::/  |::|    |/\    \  /:::/   /\   \:::\    \ 
"        /:::/  \:::\    \  /::::::V|::|    |/:::/   |::|    /::\____\/:::/___/::\   \:::\____\
"       /:::/    \:::\____\/:::/\:::\::|    |\::/    |::|   /:::/    /\:::\   \:::\   \::/    /
"      /:::/    / \::/    /\::/  \:::::|    | \/____/|::|  /:::/    /  \:::\   \:::\   \/____/ 
"     /:::/    /   \/____/  \/___/\::::|    |        |::| /:::/    /    \:::\   \:::\    \     
"    /:::/    /                    \:::|    |        |::|/:::/    /      \:::\   \:::\____\    
"   /:::/    /                      |::|    |        |::|:::/    /        \:::\__/:::/    /    
"  /:::/    /                       |::|    |        |:::::/    /          \::::::::/    /     
" /:::/    /                        |::|    |        |::::/    /            \_:::::/    /      
"/:::/    /                         \::|    |        |:::/    /               /:::/    /       
"\::/    /                           \:|    |        \::/    /                \::/    /        
" \/____/                             \|____|         \/____/                  \/____/         
"                        ----------------------
"                        |用此vim配置撸代码无BUG!|
"                        ----------------------

" ==================================================
” 键位说明
" ==================================================
" M->cmd, A->option, C->control
" <ESC> - escape, <BS> - backspace, <CR> - return
" 设置leader 键位
let mapleader= " "

" ==================================================
” 基础设置
" ==================================================
" 高亮搜索
set hlsearch
" 自动定位到输入中的字符串，不需要回车搜索
set incsearch
" 搜索时智能匹配大小写
set ignorecase smartcase
" 显示当前的模式
set showmode
" 显示行号
set number
" 显示相对行号
set relativenumber
" 光标临界行
set scrolloff=3
" 共享剪贴板
set clipboard=unnamed

" ==================================================
" 个人习惯
" ==================================================
" tab切换 下一个
nnoremap <C-m>n gt
" tab切换 上一个
nnoremap <C-m>b gT
" 格式化代码
nnoremap <C-j>f :action ReformatCode<CR>
" 移动到行首第一个字母
nnoremap H ^
" 移动到行尾最后一个字母
nnoremap L $
" 代码展开
nnoremap zi zo

" ==================================================
" 插入模式光标移动
" ==================================================
" 上下左右不需要 若要使用注意C-k与git提交快捷冲突
" inoremap <C-h> <Left>
" inoremap <C-j> <Down>
" inoremap <C-k> <Up>
" inoremap <C-l> <Right>
inoremap <C-e> <End>
inoremap <C-d> <Delete>

" ==================================================
" 多窗口操作
" ==================================================
" 清除窗口
nnoremap <Leader>wd <C-W>c
" 光标窗口切换
nnoremap <Leader>ww <C-W>w
nnoremap <Leader>wj <C-W>j
nnoremap <Leader>wk <C-W>k
nnoremap <Leader>wh <C-W>h
nnoremap <Leader>wl <C-W>l
" 纵向新增窗口
nnoremap <Leader>ws <C-W>s
" 横向新增串口
nnoremap <Leader>wv <C-W>v

" ==================================================
" IDEA预定义方法自定义快捷键
" 查看预定义方法命令 `:actionlist` 请取需要的命令设为组合键
" ==================================================
nnoremap <Leader>ga :action GotoAction<CR>
nnoremap <Leader>gc :action GotoClass<CR>
nnoremap <Leader>gd :action GotoDeclaration<CR>
nnoremap <Leader>gf :action GotoFile<CR>
nnoremap <Leader>gi :action GotoImplementation<CR>
nnoremap <Leader>gs :action GotoSymbol<CR>
nnoremap <Leader>gt :action GotoTest<CR>
nnoremap <Leader>fp :action ShowFilePath<CR>
nnoremap <Leader>rf :action RenameFile<CR>
nnoremap <Leader>se :action SearchEverywhere<CR>
nnoremap <Leader>tc :action CloseActiveTab<CR>
nnoremap <Leader>tl Vy<CR>:action ActivateTerminalToolWindow<CR>
nnoremap <Leader>? :action GotoAction<CR>
nnoremap gd :action GotoDeclaration<CR>
nnoremap gi :action GotoImplementation<CR>
" 项目搜索
nnoremap <Leader>ps :action SearchEverywhere<CR>
nnoremap <Leader>pf :action GotoFile<CR>
nnoremap <Leader>fu :action FindUsages<CR>
