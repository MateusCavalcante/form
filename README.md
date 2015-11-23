<form action="<?php echo get_option('home'); ?>" method="get">
     <input type="text" name="s" id="s" placeholder="Pesquise no site..." value="<?php the_search_query(); ?>">
    <input type="submit" value="" class="btn-search" name="" >
</form>
