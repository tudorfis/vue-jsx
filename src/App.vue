<script>
export default {
  setup() {
    const items = [ 'a', 'b', 'c' ]
    
    return () => (
        <div>
          {items.map(item => (
            <strong>{item}</strong>
          ))}
        </div>
    )
  }
}
</script>
