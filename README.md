# 🛒 React Shopping Cart - State Management Lab

A focused educational project demonstrating core React state management patterns using Context API. Perfect for understanding how to manage complex state in medium-sized applications.



## 🎯 Core Learning Objectives

### **Context API Implementation**
- Creating and consuming React Context
- Managing global state without prop drilling
- State update patterns and immutability

### **Shopping Cart Logic**
- Add/remove item functionality
- Quantity adjustment system
- Derived state (calculating totals)
- Empty state handling

### **Advanced React Patterns**
- `useImperativeHandle` for component APIs
- React Portals for modal implementation
- Forward refs usage

## 🛠️ Key Technical Implementations

| Category          | Implementations                          |
|-------------------|------------------------------------------|
| **State Management** | Context provider, Custom hooks, Action dispatch |
| **Cart Operations**  | Immutable updates, Quantity logic, Price calculations |
| **UI Patterns**      | Modal via Portal, Imperative control, Conditional rendering |

## 🧐 How to Study This Project

### Recommended Learning Path:
1. **Start with State Management**  
   Examine `ShoppingCartContext.jsx` to understand:
   - State structure
   - Available actions
   - Provider implementation

2. **Trace Data Flow**  
   Follow the component interactions:
   Product.jsx → (dispatches actions)
→ Context →
Cart.jsx/Header.jsx (react to changes)

3. **Explore Advanced Patterns**  
- Modal control in `CartModal.jsx`
- Portal usage in DOM hierarchy
- Imperative handles in action

## 🚀 Getting Started

1. Clone the repository
```bash
git clone https://github.com/sepehrshahinfar/AdvancedStateManagement.git
2. Install dependencies
npm install
3. Run the development server
npm run dev
