# Coach-Quran-
Application mobile d'apprentissage du Coran avec tadjwir.
  <TouchableOpacity style={[styles.card, {backgroundColor:'#d6e8d0'}]} onPress={()=>navigation.navigate('Recitation', {mode:'enfant'})}>
    <Text style={styles.cardTitle}>🎓 Mode Enfant</Text>
    <Text>Activités ludiques, histoires et jeux</Text>
  </TouchableOpacity>

  <TouchableOpacity style={[styles.card, {backgroundColor:'#0a4d2e'}]} onPress={()=>navigation.navigate('Recitation', {mode:'adulte'})}>
    <Text style={[styles.cardTitle, {color:'white'}]}>👤 Mode Adulte</Text>
    <Text style={{color:'white'}}>Apprentissage profond, tajwid et mémoires</Text>
  </TouchableOpacity>

  <TouchableOpacity style={[styles.card, {backgroundColor:'#f5e6c8'}]} onPress={()=>navigation.navigate('Recitation', {mode:'sage'})}>
    <Text style={styles.cardTitle}>👴 Mode Sage</Text>
    <Text>Interface simplifiée, lecture lente et guidée</Text>
  </TouchableOpacity>
</View>
