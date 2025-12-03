return {
  'nvim-tree/nvim-tree.lua',
  version = '*',
  lazy = false,
  dependencies = {
    'nvim-tree/nvim-web-devicons',
  },
  keys = {
    { '\\', ':NvimTreeToggle<CR>', desc = 'File explorer reveal', silent = true },
    { '<leader>ef', ':NvimTreeFindFile<CR>', desc = 'Focus file on explorer' },
  },
  config = function()
    require('nvim-tree').setup {
      view = {
        width = 40,
      },
    }
  end,
}
