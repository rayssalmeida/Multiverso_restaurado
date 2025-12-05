# Multiverso_restaurado

# 🎮 Multiverso Database

Banco de dados MongoDB com personagens de múltiplos universos (animes, games, filmes, HQs).

## 📊 Estrutura do Banco

### Coleções:
1. **universes** - Universos ficcionais
2. **species** - Espécies/raças dos personagens  
3. **equipment** - Equipamentos icônicos
4. **movies** - Obras audiovisuais
5. **characters** - Personagens principais

### Relacionamentos:
- characters.universe_id → universes._id
- characters.species_id → species._id  
- characters.equipment_ids → equipment._id
- characters.m
