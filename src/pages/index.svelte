<script>
    import Navigation from "./../components/Navigation/Navigation.svelte";
    import { metatags } from '@roxi/routify'
 
     import { url } from '@roxi/routify'
     console.log($url())
 
    metatags.title = 'My Routify app'
    metatags.description = 'Description coming soon...'
</script>

 
<Navigation/>
 
<a href={'./shop'}>
    Shop
</a>
<a href={'./'}>
    home
</a>