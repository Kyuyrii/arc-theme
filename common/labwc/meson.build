foreach variant : get_option('variants')
  target_install_dir = prefix / install_dir.get(variant) / common_dirs.get('labwc')
  
  labwc = ''
  if variant == 'dark' or variant == 'darker'
    labwc = 'labwc-Dark'
  else
    labwc = 'labwc'
  endif

  install_subdir(
    labwc,
    install_dir : target_install_dir,
    strip_directory : true
  )
endforeach
